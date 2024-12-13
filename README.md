# Next.js 15 App Router Unexpected Behavior

This repository demonstrates an unexpected behavior in Next.js 15's App Router when combining dynamic routes and `getStaticProps`.  The issue arises when attempting to fetch data for a dynamic route using `getStaticProps`.

## Bug Report

The provided code shows a simple Next.js 15 App Router implementation with a dynamic route.  When navigating to a dynamic route, the data fetched by `getStaticProps` is not correctly passed to the page component.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the development server using `npm run dev`.
4. Navigate to a dynamic route like `/product/1`.
5. Observe the unexpected behavior.

## Expected Behavior

The page should display the data fetched by `getStaticProps`.

## Actual Behavior

The page component receives `undefined` instead of the expected data.

## Additional Information

* Next.js version: 15.0.0 (or latest)
* Operating System: [Your OS]
* Browser: [Your Browser]