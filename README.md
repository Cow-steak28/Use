

At ClassroomCommunity.com, we are dedicated to fostering a vibrant and inclusive community within classrooms. Our platform is designed for students and educators to connect, share, and grow in a supportive environment. Here, you can engage with your peers, access educational resources, enjoy entertaining content, and find a relaxing space tailored to enhance your learning experience. Join our community today and enrich your educational journey with meaningful connections and endless learning opportunities!

This website is powered by Interstellar code, a project licensed under the GNU Affero General Public License (AGPL) Version 3, dated 19 November 2007. Our modifications and additional source code are available under the same license and can be accessed at GitHub.

## ClassroomCommunity modifications:
- branded the website under Classroom Community name;
- UI changes on tabs page;
- changed json for games and apps;
- integrated disqus;



## Interstellar
<div align="center">
    <img src="https://raw.githubusercontent.com/UseInterstellar/Interstellar/main/.github/branding/in.png">
    <p>Interstellar is a web proxy with a Clean and Sleek UI and easy to use menus. Our goal is to provide the best user experience to everyone.</p>
</div>

![inpreview](https://github.com/InterstellarNetwork/Interstellar/assets/89202835/2669efed-5186-4932-83c4-725acae60bd2)

> [!IMPORTANT]
> If you fork this project, consider giving it a star in the original repository!

**Join Our [Discord Community](https://discord.gg/interstellar) for support, more links, and an active community!**

## Features

- About:Blank Cloaking
- Tab Cloaking
- Wide collection of apps & games
- Clean, Easy to use UI
- Inspect Element
- Various Themes
- Password Protection (Optional)
- Built-in Tab System
- Now.gg Support
- Fast Speeds
- Geforce NOW Support

## Deployment

> [!IMPORTANT]
> You **cannot** deploy to static web hosts, including Netlify, Cloudflare Pages, and GitHub Pages.

### Server Deployment

You must run these commands on your server:  
`git clone https://github.com/InterstellarNetwork/interstellar`  
`cd interstellar`  
`npm install`  
`npm start`

### Updating

`cd interstellar`  
`git pull --force --allow-unrelated-histories`

<a target="_blank" href="https://heroku.com/deploy/?template=https://github.com/interstellarnetwork/interstellar"><img alt="Deploy to Heroku" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/heroku.svg"></a>
<a target="_blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/interstellarnetwork/interstellar"><img alt="Deploy to Koyeb" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg"></a>
<a target="_blank" href="https://app.cyclic.sh/api/app/deploy/interstellarnetwork/Interstellar"><img alt="Deploy to Cyclic" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/cyclic.svg"></a>

### Deployment Alternatives

For more deployment options, join our [Discord Server](https://discord.gg/interstellar) for various ways to deploy Interstellar.
This includes methods of deploying to Render/OnRender.

#### What happened to Replit Deployment?

As of January 1st, 2024, Replit is [no longer free](https://blog.replit.com/hosting-changes). Try GitHub Codespaces instead.

### GitHub Codespaces

1. Create a GitHub account if you haven't already.
2. Click "Code" (green button) and then "Create Codespace on main."
3. In the terminal at the bottom, paste `pnpm i && pnpm start`.
4. Respond to the application popup by clicking "Make public."
   > [!IMPORTANT]
   > Make sure you click the "Make public." button, or the proxy won't function properly.
5. Access the deployed website from the ports tab.
6. For subsequent uses in the same codespace, just run `pnpm start`

### Solution for if there is no popup.

1. Run `pnpm i`, and before `pnpm start`, prepend `PORT=8080`, replacing 8080 with another port. For example, `PORT=6969 pnpm start`.
2. If this does not work then you can prepend `$env:PORT=8080;`, replacing 8080 with another port. For example, `$env:PORT=6969; pnpm start`
3. Go to the ports tab, Click Forward A Port, And type the port number.
4. Right-click Visibility and set Port Visibility to Public.

> [!NOTE]
> We are committed to making Interstellar easy and personalized however, as of now we need your support in making it ad-free. Consider keeping ads so Interstellar can run freely or contribute by being a supporter.

## Report Issues

If you encounter problems, open an issue on GitHub, and we'll address it promptly.

> [!TIP]
> If you're having trouble, don't hesitate to reach out to us on [Discord](https://discord.gg/interstellar) for personalized support.

# Credits

A huge thanks goes out to all of the people who have contributed to Interstellar.

[![Contributors](https://contrib.rocks/image?repo=InterstellarNetwork/Interstellar)](https://github.com/InterstellarNetwork/Interstellar/graphs/contributors)
