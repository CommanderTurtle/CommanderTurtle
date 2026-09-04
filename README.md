<details>
  <summary>click to expand</summary>

### Agent Infrastructure Projects:

https://github.com/CommanderTurtle/persephone just my integration of own internal config + continuity with omp. 
gpu & local-only for just about everything so far

- [Diogenes](https://github.com/CommanderTurtle/diogenes) - hosting (linux, service manager), maintained fork of Odysseus for backends and control center
— this can install and integrate the following if not already installed:

- [sandwich](https://github.com/CommanderTurtle/sandwich) - node package management/auditing for all these package.jsons 
- [libriarian](https://github.com/CommanderTurtle/librarian) - wikifier (makes wikis, dreaming agents)
- [retrieval](https://github.com/CommanderTurtle/retrieval) - skill labrador that fetches necessary skills from archive on disk, rather than bloating agent prompt with full list
- [persephone](https://github.com/CommanderTurtle/persephone) - adds omp (pi agent) gateway layer
- [leetcoder](https://github.com/CommanderTurtle/leetcoder) - allows hermes to puppeteer pi’s for small coding tasks (delegation)

Lots of ideas from stablyai/orca, which does all these things, and where i got a lot of inspiration for the ecosystem

Still WIP. Doing lots of editing as I continue development. Especially with Diogenes automatically setting up my config upon install

### Web-Development:

- [orc](https://github.com/CommanderTurtle/orc) - a multisite/multiframework F# engine for modular websites in py, ts, c#, js, and ruby.
- [reactor](https://github.com/CommanderTurtle/reactor) - a lightweight rust-poller that allows for a live fsharp repo in 7+ languages. Side-hosts vite dev server, zensical serve, jekyll serve, netdocs serving (C#), and more with [preview](https://github.com/CommanderTurtle/preview)
- [tools](https://github.com/CommanderTurtle/tools) - just some lightweight tools that help making maintaining websites easy in modular languages

### Libraries:

- [regedited](https://github.com/CommanderTurtle/regedited) - for databases
- [macrohelp](https://github.com/CommanderTurtle/macrohelp) - for macros
- [firebending](https://github.com/CommanderTurtle/firebending) - an Anything-MCP built on macrohelp (TBD)

### Apps:

- [app/adspace](https://app.shel.sh/adspace/templates/1) - ad simulator
- [app/countku](https://app.shel.sh/countku) - count in haiku

### JS Abominations:

- [Webclip](https://app.shel.sh/webclip) -- "Webclipper" - scrape the web to markdown. -> Reliant on firecrawl/anydoc wasm
- [LLM 🤖](https://llm.shel.sh/) -- A static page harness entirely without a DB. -> Reliant on tesseract OCR wasm, plus more anydoc wasm.
- [ln-kr](https://a.shel.sh) -- a.shel.sh Project - App for link compression. <a href="https://a.shel.sh/#m:IM(jO..#cZQ7)Mar'Jd,oN8Uj9~E6(rPb@HTB-,1WC#/$]'xIPe5[yHjpm&:0LDk.kEIS?X;9nd2EAD/32o&o-M's+LX[!LI~Cd=3J?bf$8(=j5J)#QXt/4kQRfrl,x)8q&syx*:2n5KI3P?IVXmZ$Y#Wf$to0;W2VO2esFg'aw~Gr]aS,17jU8pmh7&z(4uyFJr!+c(kZ1N#wIT$.&e6w.q)LRhoZB!g&Su#VZEZ]pJ8(0xJrRu8:]Ipw@h=-MfV,UuRkhlP[5Guee*cZ[zAwL*i8Y$dAI#ZN;8Bc*=ekvnwaoe@.#YlY+IxGf*?EZ'8OkwDQAT6+GW2A)X!8y~:-.+-Yx70ux5N5O_2p2$u7.Foz?q-&uMJ'NN(b(bNj_ysO5SlI0AO]vh*X)GHauamRfXiq#MOO=+6y0sLa#S7W4UM8Evo-+j?~N5:?Ej8uvo2EZ!W44e$KbH@r+Dy#Mr7:.mrR4wQY9(Tt~UahxP/ei'hFWvj-+5,D?se7/7--msig28'2;w_e]PnwcXBZ@-~@8d.HrfgxvQMzIK0Y#K8LB[KBOxAd(fsyw#_w~Wh5g&@gE&/A+fJZ5q/0/cbvdDVUU0!7;eXHJB$~nZ]?@_jrRSpXg+HNAiL]ZPD:_W/$Bd$SFM[Ns~_x(7b'SQ4jT[[o17CqFnXw#jr60~G]Zr_k$uFOXt6GU.gijy0U@.v~*.CjCH@oYG.kyg])FI&c&H:Jes6r=TP-Utrc-5oYu?i13R,j~N[~re!,/B8.'6Q-WmO&Esy'6?a*rTv1uldu(I/t*YX5s0&f/5(M;!iJvEyh+#]0zLT36?eO9(pWBIjWl6TTqp[tz5EkInyHLNdfWyWKxh#PGYAuJ6kE50pq0[F12rOO'3@nU=/vc'FeagNxz?XV/lgEOOX9xBS9=X6Sn8_Iq-YY~,9V1+L*8/2&zB!52wAX[*$/lX*SEH]&cNk5/xa(=it83~i*dhjtomWnt1ne.R,w+0.Uvm[uQ7ugyCON3/=cxQzLuv,aG0bHa2I7-hp_..8z3G?3;jZaeJ=GhDz@,KfY'sC)EVd(5([9/g/zRV]lS8efB0mZxBUpZcm*ytOL34zT~Vk*hd9z~Lg65F)XI/HO?hU8ii*]vu'/aenit#FX&4!WncCtJPrwzmQ)T8hxO[ZR@Nx+*kGyQcg!gjH$MIB*.5iXOvJR3=J3Aol?43Kv_W889ye1JD?#cFGz#Sf*9V!m_DMW#Paxe#$qlNoVu(r/G'Hkac4D]f),po?uAxk?dm:x4o4Br=_WiS2)AOdQw[stLYSK,/-[AzqU1M=qFc1,RO:yAKl@sVPICxWrM3DEVNwe8R-9/]k1KQH'Z/4Z~yG=,:l(6hgf#a(e=IL=-cun(kTXD[f(1Zw[GemB:~otjy9+?Mq+kv5R0N1S9=qF4+ksd+'aBvd8'6(d0YAyLk65bNU?nDv9XvLHR41?uOO9,p=sw)bd,Z'7TF8#LlnFnCE!aEBH2Q$lT:YLyY.Wa1pVHYM@I[dLrFDiz)U;Lnd&/_=LfdVEw@zd9l~dtJ:fzT!AWUz[#/o4wDE#Th]T-0wuqOf9wmBB0+pundy4p[.r4JaP,dS4Au1kw2Q'F[U'=f-~E/kDI$2LfE6xEnN,i$q_7??eQ3qLwAr3[0IOF3YSBgT~myDC+Y/R?x/'Mq&E/+kUYlDT~!t~&CNI)*o*PnswzPX8s&lZ$PtzA3t@=Qn)QTv6qBJJkC!~EZOzp#6~tk(A&#@S[h(2?Cv]w@q7Tv_XPTW,kiH-lH.od]-,GM&Z?#N'v+DJjx)k*W#ZO)Wr97Rj6wOTus#4/b)8u/EbP1R$;3elYq[TNfwtC-[?Xi:oSom?,5s'E.)~PI*_Hx['EhNYvi)V'UD(Q*y[peeh]U1tT_uB;?PrCD@,QLCRyx+=bwHyA_P+(O:4d_C~2hEt5,6k$-XlcE'h$)$4V.LC:_UgeO&2bi/Y,BS7awbSF!'lp-s=y@exa#n!'gX)Ur5'h@]CmOz?#oSZx_Y7xBi20R9uO2=W#sc3w6h,fkv'jPJV*q/5Yn#ot~lXRFTruTsPfBbPnC@6t@r]&LOP[Z(*rX@Jht47DxOmD?6mo$u-5]XhMA_]K!n,V9+K3;b;i$#3N]*jFz)2@?DMix,U#)zkMKDc0q6@7xTL:]'-@8h.LZs'Wnpc/c@cTM2Xr;_Mkvk**O81PG]mCGih_4uvPuOnufp+Ejt:B]m~nJ,iN6!+lih9/=ROhO_M0HI_.OUT]Of0,8vWzJl0-JywGF*8UGXpIGgCqv1~9Lm,yZrVmD?H[Zn5O7!O_xP10)kB[S2)+HOft+3Zy,mbjy)-rytw9Z7$KBtmJ2gG.$((TdT4&sR18W#oy(aYb56C6#T?sB6VNOWVd.oh6qr./Am;AwCJDSd0IWImv+ysK~S,zM]RTPSB_9F8@xk[gnd0+D4&" title="Did I reinvent Jupyter Notebooks?"> Did I reinvent Jupyter Notebooks? Yes. </a>
- [make-it](https://app.shel.sh/make) -- "Make-It" - A fork of convert.to.it running entirely within a static page. <a href="https://a.shel.sh/#m:_o4rTmC(MEez-5PFY2eSyNe1zCQ*njM-s-G'ToqY7FTE6!-2LXG4mF1u.jIIt:-E6M($]I?;[jS2y)dD*2:z]BMkkVQNy8t(k8bFeiXNR2V7#m*pu$ckomlXz.Mtn+u4'/#tGjCkX]juN~54cciTD+YPcRRDDf#X5CV#oVA0&.JxE)o-Fi(3ViJ$d3y.1L_KIf$x;FVLjd#W?MGFO.+LHQE45+XEe7U/SQ[Ww-gZy:?=B;7D?AQG+XH2l_H#,-ysEQZjbt8HnQoNOj-(VsWyG$D=dBJkuv]!y~WI,q:+[!nV)TA9zwyDVc_giR#?;UqoZM8f4Bot[ZN+@W,h2Rb7j#udB*#n-nISeU442uCB]2=@D?_Exur)VvJ=?E[f5.4Z[su:qM]CopMb;FENR!9dd@dchh-,HNf?qE8vsCJmKOQ'GuP:#K)Kn-V/oqOAK*:,IxWvsG(HI+~LEVwAvJey+dvvJkg157UZLGIHzu@" title="Document Sharing"> With inbuilt document sharing</a> & OCR pipelines
- [Radio](https://app.shel.sh/radio) - A Radio. Forked the omarchy plugin store to be solely webapps, [here](https://github.com/CommanderTurtle/omarchy-webapp-shell).

### Multimedia:

- [mm-tools](https://github.com/CommanderTurtle/mm-tools) - Locally hosted AI multimedia frontends
- [seamingly-epic](https://github.com/CommanderTurtle/seamingly-epic) - A mathematical seam project to allow for 8k Nvidia PID Generation
- [vox](https://github.com/CommanderTurtle/vox) - A Rust native program wired up to the `mm-tools` repo. Use local LLMs in a local mv3 extension on Edge. Subtitle things with Speech-To-Text. A native mic-router with VB-Cable. Lots of things.

</details>
