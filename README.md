# React Router v6 Nested Route Issue with Wildcard Parent Route

This repository demonstrates a subtle bug in React Router v6 related to nested routes within a parent route using a wildcard path.  The issue arises when attempting to nest routes under a parent route that uses a wildcard (`*`).  The nested routes will not render correctly in this scenario.  The provided solution demonstrates a workaround.

## Bug Description

The bug occurs when combining wildcard routes with nested routes in React Router v6. The nested routes fail to mount, resulting in a broken navigation experience.

## Solution

The proposed solution involves restructuring the routes to avoid nesting under a wildcard route.  This can often be achieved by re-evaluating the route structure or by using more specific paths.