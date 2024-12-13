# React Router Catch-All Route Conflict

This repository demonstrates a common issue with React Router's catch-all route (`*`). When not carefully placed, the catch-all route can unintentionally intercept other routes, resulting in unexpected page rendering or navigation problems. The conflict arises when the catch-all route is not specific enough, causing it to match routes it shouldn't. 

The `App.js` file demonstrates the problematic code, while `AppSolution.js` showcases how to resolve this by carefully ordering routes and ensuring specificity.