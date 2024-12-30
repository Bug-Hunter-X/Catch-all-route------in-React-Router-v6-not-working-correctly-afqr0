# React Router v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router v6.  The `NotFound` component is always displayed, regardless of whether other routes match.

## Problem

The issue is that the catch-all route is always matched, even when a specific route should match first.  This prevents the correct component from rendering when using multiple routes.

## Solution

The solution provided in the `App.js` file shows how to modify the route structure to prioritize specific routes before the catch-all route.

This problem can be avoided by ordering the routes to ensure more specific routes are checked before the catch-all.
