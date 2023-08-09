### Hi there 👋

I am Nivekithan S, I am fullstack developer currently working in [Magic](https://www.linkedin.com/company/usemagic) in the role Product Engineer (Backend). 

### Work Experience 

I am working as Product Engineer at [Magic](https://www.linkedin.com/compay/usemagic) since August 2022. Some of my notable achievements include 

1. Designed and implemented a feature that sends more than 10,000 slack DM messages while also respecting the slack ratelimit using bull queue
2. Successfully transformed monolithic backend into separate job and request services, significantly reducing memory and CPU usage. This ensured seamless operation during high job loads.
3. Contributed to the development of a payment gateway for the events system, empowering our customers to seamlessly utilize Stripe for event-related transactions.
4. Worked on setting up Prometheus, Loki, Grafanna for our frontend and backend service while also making minimal changes to our codebase so that we can continuously develop our product.  
5. Contributed to migrating our service from Digital Ocean to AWS leading to improved performance of our product
6. Took ownership and created a `cli` tool that initializes our development environment locally after one of our new hires took more than two days to setup the development environment locally.
7. Took ownership and orchestrated a gradual transition of our product's codebase from Javascript to Javascript with `JsDoc` leading to less runtime errors and better DX without compromising development timelines for ongoing features.

### Projects 

Whenever I get free time, I like to work on projects to satisfy my curiosity about new technologies and understand their tradeoff compared to current technologies. 

## Key Manager 

In my work most of the time I have to write code that respects the ratelimit of slack APIs. One time I had a bug that caused an infinite loop hitting the slack API, ofcouse I got ratelimited and slack API continues to function normally without affecting other users. There must be thousands of other programmers who must have done the same mistake still, slack APIs continuously work for everyone. What's one main reason behind this? their rateliimt algorithm.

So when I came across [shadcn/ui](https://ui.shadcn.com/), [fly.io scale to zero vm's](https://fly.io/) and [webauth by Passage](https://passage.1password.com/) I have decided to build this project.

- Live Version: https://key-manager.nivekithan.com
- Github Repo: https://github.com/nivekithan/key-manager
- Docs website: https://docs-key-manager.nivekithan.com
- npm package: https://www.npmjs.com/package/@niveth/key-manager

## Responsive Screenshot 

I came across this tool [Full page screenshots](https://damngood.tools/tools/full-page-screenshots) which allows you to take full page screenshots of a website. The first thing that came to my mind after seeing this tool is how easy it will be for non-technical managers if they can just take a screenshot of their websites in multiple viewport and compare it to provide any feedback. 

So with [shadcn/ui](https://ui.shadcn.com) and [appwrite](https://appwrite.io/), I have decided to build this project 

- Live version: https://responsive-screenshots.nivekithan.com
- Github Repo: https://github.com/nivekithan/responsive-screenshot

> ### Similar Project 
>
> https://screenshot.nivekithan.com is a similar project which takes a single screenshot of a website with a selected device type. I have used [cloudflare Browser rendering API](https://developers.cloudflare.com/browser-rendering/) for taking screenshots. The API is still not ready for production since it has limits of only creating two new browser instances per minute. Right now I am working on a workaround using [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) 
>
> - Live version: https://screenshot.nivekithan.com
> - Github Repo: https://github.com/nivekithan/screenshot-page

## Path Finder 

It is one of the first projects I did as a beginner, I was learning about path-finding algorithms and I thought how fun it will be if I implemented a visualizer for the algorithm.  

- Live Site: https://path-finder-brown.vercel.app/
- Github Repo: https://github.com/nivekithan/path-finder

## Slatejs Devtools 

`slate-js` is a library for creating a rich text editor. When I was a beginner I was working on creating a clone of notion, which lead me to `slate-js`. Notion text editor is hugely complex. Whenever I run into bugs while implementing those features using `slate-js` it used to take me a long time to pin down the bug.

That's when I decided to build `slate-js-devtools` to make my debugging experience better. 

- npm package: https://www.npmjs.com/package/slate-devtools
- Github Repo: https://github.com/nivekithan/slate-devtools

### Fly.io Distributed System Challenges

Doing a full-stack project is a huge time commitment. That's I prefer to do challenges when I want to learn a particular concept with clearly defined requirements and constraints.  

One of those challenges is [Fly.io Distributed system challenges](https://fly.io/dist-sys/)

Till now I have completed these challenges 

1. Echo - https://fly.io/dist-sys/1/
2. Unqiue Id generateion - https://fly.io/dist-sys/2/
3. Single Node Broadcast - https://fly.io/dist-sys/3a/
4. Multi Node Broadcast - https://fly.io/dist-sys/3b/
5. Fault-Tolerant Broadcast - https://fly.io/dist-sys/3c/
6. Efficiency Broadcast - https://fly.io/dist-sys/3d/

You can check my solutions at [Solution for fly.io challenge using deno](https://github.com/nivekithan/deno-fly)
