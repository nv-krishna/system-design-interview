# Content Delivery Network

## Concepts
- Geographically distributed network of proxy servers and their data centers.

## Functionalities
- Serve content from locations closer to the user.

## Pros
- High availability.
- Better performance.

## Cons
- CDN costs could be significant.
- Content might be stale.
- CDNs require changing URLs for static content to point to the CDN.

## Types
- Push
   - You upload new content from your server to CDN when the content is new or changed.
- Pull
   - CDN grabs new content from your server to itself when the first user requests the content.
