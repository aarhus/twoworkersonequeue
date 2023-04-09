# Cloudflare Queues in Miniflare

This is two workers which are bound to a queue and that can be tested from within Miniflare

## How to run it?

Clone the repository

    cd consumer && npm install
    npm install

    npm run dev

Then just point your browser at the URL in the miniflare output and it will send the headers of the request into the queue.
