# Big-AGI jcachat fork


check out big-agi.com for the official project


## install & run locally

```md
Build-your-own
If you want to change the code, have a deeper configuration, add your own models, or run your own instance, follow the steps below.
Prerequisites: Node.js and npm installed on your machine.

Clone the big-AGI repository:
`git clone https://github.com/enricoros/big-AGI.git`
`cd big-AGI`

Install dependencies:
`npm install`

Run the development server:
`npm run dev`

Your big-AGI instance is now running at http://localhost:3000.
Local Production build
The production build is optimized for performance and follows the same steps 1 and 2 as for local development.

Build the production version:
# .. repeat the steps above up to `npm install`, then:
npm run build
Start the production server (npx may be optional):
npx next start --port 3000
Your big-AGI production instance is on http://localhost:3000.
Advanced Customization
Want to pre-enable models, customize the interface, or deploy with username/password or alter code to your needs? Check out the Customizations Guide for detailed instructions.
```



## sync my repo with new updates in OG

```md
# 1. Navigate to your local repo
cd /jcachat/BIG-AGI

# 2. Ensure you are on your specific branch
git checkout v2-main

# 3. Add the upstream remote (if you haven't already)
git remote add upstream https://github.com/enricoros/big-AGI.git

# 4. Fetch the latest info from the upstream
git fetch upstream

# 5. Merge the upstream 'main' into your 'v2-main'
git merge upstream/main
```

