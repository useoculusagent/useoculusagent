<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0f1a,50:0a0f1a,100:0052FF&height=260&section=header&text=Oculus&fontSize=88&fontColor=ffffff&fontAlignY=38&desc=spending%20guardrails%20for%20AI%20agents%20on%20Solana&descAlignY=62&descSize=18&animation=fadeIn" width="100%" alt="banner"/>

<a href="https://github.com/useoculusagent">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=0052FF&center=true&vCenter=true&width=860&lines=on-chain+policy+enforcement+for+agent+wallets;every+tx+verified+on+Solana;automatic+USDC+refund+if+a+budget+breaks;built+on+anchor+%2B+helius+%2B+fastapi" alt="typing"/>
</a>

<br/><br/>

<a href="https://github.com/useoculusagent"><img src="https://komarev.com/ghpvc/?username=useoculusagent&label=profile+views&color=0052FF&style=flat-square" alt="views"/></a>
<a href="https://github.com/useoculusagent?tab=followers"><img src="https://img.shields.io/github/followers/useoculusagent?style=flat-square&color=0052FF&labelColor=0a0f1a&label=followers" alt="followers"/></a>
<a href="https://github.com/useoculusagent/oculus-program/stargazers"><img src="https://img.shields.io/github/stars/useoculusagent/oculus-program?style=flat-square&color=0052FF&labelColor=0a0f1a&label=stars" alt="stars"/></a>
<a href="https://x.com/oculusagent_"><img src="https://img.shields.io/badge/follow-%40oculusagent__-0052FF?style=flat-square&logo=x&logoColor=white&labelColor=0a0f1a" alt="twitter"/></a>

</div>

<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/useoculusagent/useoculusagent/output/github-contribution-grid-snake-dark.svg">
  <img alt="snake" src="https://raw.githubusercontent.com/useoculusagent/useoculusagent/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>
</div>

<br/>

## ◆ &nbsp; what is Oculus

Spending guardrails for autonomous AI agent wallets on **Solana**.
Every transaction is checked on-chain against a policy. If it breaks the budget, the agent's USDC reserve **reimburses the loss within 60 seconds** — no human in the loop.

```ts
import { OculusClient } from "@oculus/sdk";

const oculus = new OculusClient({ connection, vault });

oculus.on("policy.breach", async (ev) => {
  console.log(`agent broke budget by ${ev.deltaUsd} USDC`);
  await oculus.refund(ev.signature);
});
```

<br/>

## ◆ &nbsp; stats

<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=useoculusagent&show_icons=true&theme=transparent&hide_border=true&bg_color=0a0f1a&title_color=0052FF&icon_color=0052FF&text_color=c9d1d9&include_all_commits=true&rank_icon=github"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=useoculusagent&layout=compact&theme=transparent&hide_border=true&bg_color=0a0f1a&title_color=0052FF&text_color=c9d1d9&langs_count=6"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=useoculusagent&theme=transparent&hide_border=true&background=0a0f1a&stroke=0052FF&ring=0052FF&fire=0052FF&currStreakLabel=0052FF"/>
</div>

<br/>

## ◆ &nbsp; pinned

<table>
<tr>
<td width="50%" valign="top">

#### [oculus-program](https://github.com/useoculusagent/oculus-program)
<a href="https://github.com/useoculusagent/oculus-program">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=useoculusagent&repo=oculus-program&theme=transparent&hide_border=true&title_color=0052FF&icon_color=0052FF&text_color=c9d1d9&bg_color=0a0f1a"/>
</a>

</td>
<td width="50%" valign="top">

#### [oculus-sdk](https://github.com/useoculusagent/oculus-sdk)
<a href="https://github.com/useoculusagent/oculus-sdk">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=useoculusagent&repo=oculus-sdk&theme=transparent&hide_border=true&title_color=0052FF&icon_color=0052FF&text_color=c9d1d9&bg_color=0a0f1a"/>
</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [oculus-webhook](https://github.com/useoculusagent/oculus-webhook)
<a href="https://github.com/useoculusagent/oculus-webhook">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=useoculusagent&repo=oculus-webhook&theme=transparent&hide_border=true&title_color=0052FF&icon_color=0052FF&text_color=c9d1d9&bg_color=0a0f1a"/>
</a>

</td>
<td width="50%" valign="top">

#### links

- [oculusagent.xyz](https://oculusagent.xyz)
- [@oculusagent_](https://x.com/oculusagent_)
- [@oculus/sdk on npm](https://www.npmjs.com/package/@oculus/sdk)
- [policy program (anchor)](https://github.com/useoculusagent/oculus-program)

</td>
</tr>
</table>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0052FF,50:0a0f1a,100:0a0f1a&height=120&section=footer&animation=fadeIn" width="100%" alt="footer"/>
</div>

