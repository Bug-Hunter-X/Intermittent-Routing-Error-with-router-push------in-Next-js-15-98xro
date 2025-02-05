# Intermittent Routing Error in Next.js 15

This repository demonstrates an intermittent routing error encountered in Next.js 15 when using `router.push('/')` to redirect from a page to the homepage.  The issue is not consistently reproducible, but it appears related to client-side rendering and the timing of the redirect.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to the `/about` page.
5. Click the "Go to Home" button.

Sometimes the redirect to the homepage works correctly. Other times, the page will appear blank or throw a routing error.  The behavior is inconsistent, making debugging difficult. 

## Potential Solutions

The solution file (aboutSolution.js) provides a workaround that enhances the reliability of the routing by explicitly setting the page transition state.

## Technologies Used

* Next.js 15
* React

## Contributing

Contributions are welcome!  Please open an issue or submit a pull request if you have any suggestions or improvements.