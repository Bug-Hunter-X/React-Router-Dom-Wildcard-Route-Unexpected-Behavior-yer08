# React Router Dom Wildcard Route Issue

This repository demonstrates an unexpected behavior with the wildcard route (`/*`) in React Router Dom v6.  The wildcard route is incorrectly triggered, even when a valid route exists.  The solution provides a corrected approach to ensure proper route matching.

## Problem

The provided code uses a wildcard route (`/*`) to handle 404 errors. However, even if a matching route exists, the wildcard route is activated. This makes the application show the 404 page even for valid paths.