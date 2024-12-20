# Next.js 15 App Router Link Component Issue

This repository demonstrates a common issue encountered when migrating or working with Next.js 15's App Router and the `next/link` component.

The problem arises when using the `next/link` component within a page that is using the Pages Router, especially when there's a mismatch between the routing conventions of the two systems. This can result in unexpected navigation behavior or rendering problems. 

## Bug Description
The `Link` component may not navigate correctly, or might trigger unexpected page rendering issues when transitioning between pages if not properly configured for App Router.