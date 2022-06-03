(function(g){var window=this;'use strict';var I3=function(a){g.V.call(this,{F:"div",L:"ytp-miniplayer-ui"});this.Ve=!1;this.player=a;this.P(a,"minimized",this.ah);this.P(a,"onStateChange",this.xJ)},J3=function(a){g.lJ.call(this,a);
this.j=new I3(this.player);this.j.hide();g.YI(this.player,this.j.element,4);a.Af()&&(this.load(),g.M(a.getRootNode(),"ytp-player-minimized",!0))};
g.w(I3,g.V);g.k=I3.prototype;
g.k.bH=function(){this.tooltip=new g.wN(this.player,this);g.H(this,this.tooltip);g.YI(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.Bc=new g.tK(this.player);g.H(this,this.Bc);this.Fh=new g.V({F:"div",L:"ytp-miniplayer-scrim"});g.H(this,this.Fh);this.Fh.xa(this.element);this.P(this.Fh.element,"click",this.CC);var a=new g.V({F:"button",Ba:["ytp-miniplayer-close-button","ytp-button"],T:{"aria-label":"Close"},R:[g.zG()]});g.H(this,a);a.xa(this.Fh.element);this.P(a.element,"click",this.Lj);
a=new g.QZ(this.player,this);g.H(this,a);a.xa(this.Fh.element);this.jr=new g.V({F:"div",L:"ytp-miniplayer-controls"});g.H(this,this.jr);this.jr.xa(this.Fh.element);this.P(this.jr.element,"click",this.CC);var b=new g.V({F:"div",L:"ytp-miniplayer-button-container"});g.H(this,b);b.xa(this.jr.element);a=new g.V({F:"div",L:"ytp-miniplayer-play-button-container"});g.H(this,a);a.xa(this.jr.element);var c=new g.V({F:"div",L:"ytp-miniplayer-button-container"});g.H(this,c);c.xa(this.jr.element);this.xQ=new g.UL(this.player,
this,!1);g.H(this,this.xQ);this.xQ.xa(b.element);b=new g.SL(this.player,this);g.H(this,b);b.xa(a.element);this.nextButton=new g.UL(this.player,this,!0);g.H(this,this.nextButton);this.nextButton.xa(c.element);this.Ih=new g.iN(this.player,this);g.H(this,this.Ih);this.Ih.xa(this.Fh.element);this.uc=new g.eM(this.player,this);g.H(this,this.uc);g.YI(this.player,this.uc.element,4);this.rC=new g.V({F:"div",L:"ytp-miniplayer-buttons"});g.H(this,this.rC);g.YI(this.player,this.rC.element,4);a=new g.V({F:"button",
Ba:["ytp-miniplayer-close-button","ytp-button"],T:{"aria-label":"Close"},R:[g.zG()]});g.H(this,a);a.xa(this.rC.element);this.P(a.element,"click",this.Lj);a=new g.V({F:"button",Ba:["ytp-miniplayer-replay-button","ytp-button"],T:{"aria-label":"Close"},R:[g.FG()]});g.H(this,a);a.xa(this.rC.element);this.P(a.element,"click",this.SZ);this.P(this.player,"presentingplayerstatechange",this.Wc);this.P(this.player,"appresize",this.vb);this.P(this.player,"fullscreentoggled",this.vb);this.vb()};
g.k.show=function(){this.ue=new g.Lo(this.hs,null,this);this.ue.start();this.Ve||(this.bH(),this.Ve=!0);0!==this.player.getPlayerState()&&g.V.prototype.show.call(this);this.uc.show();this.player.unloadModule("annotations_module")};
g.k.hide=function(){this.ue&&(this.ue.dispose(),this.ue=void 0);g.V.prototype.hide.call(this);this.player.Af()||(this.Ve&&this.uc.hide(),this.player.loadModule("annotations_module"))};
g.k.ea=function(){this.ue&&(this.ue.dispose(),this.ue=void 0);g.V.prototype.ea.call(this)};
g.k.Lj=function(){this.player.stopVideo();this.player.Ma("onCloseMiniplayer")};
g.k.SZ=function(){this.player.playVideo()};
g.k.CC=function(a){if(a.target===this.Fh.element||a.target===this.jr.element)this.player.S().K("kevlar_miniplayer_play_pause_on_scrim")?g.BF(this.player.wb())?this.player.pauseVideo():this.player.playVideo():this.player.Ma("onExpandMiniplayer")};
g.k.ah=function(){g.M(this.player.getRootNode(),"ytp-player-minimized",this.player.Af())};
g.k.Sd=function(){this.uc.Qb();this.Ih.Qb()};
g.k.hs=function(){this.Sd();this.ue&&this.ue.start()};
g.k.Wc=function(a){g.U(a.state,32)&&this.tooltip.hide()};
g.k.vb=function(){g.uM(this.uc,0,this.player.Wa().getPlayerSize().width,!1);g.hM(this.uc)};
g.k.xJ=function(a){this.player.Af()&&(0===a?this.hide():this.show())};
g.k.jc=function(){return this.tooltip};
g.k.Hf=function(){return!1};
g.k.hg=function(){return!1};
g.k.Cj=function(){return!1};
g.k.Cz=function(){};
g.k.ap=function(){};
g.k.uu=function(){};
g.k.yp=function(){return null};
g.k.Yx=function(){return null};
g.k.Gk=function(){return new g.Ml(0,0,0,0)};
g.k.handleGlobalKeyDown=function(){return!1};
g.k.handleGlobalKeyUp=function(){return!1};
g.k.zs=function(a,b,c,d,e){var f=0,h=d=0,l=g.im(a);if(b){c=g.To(b,"ytp-prev-button")||g.To(b,"ytp-next-button");var m=g.To(b,"ytp-play-button"),n=g.To(b,"ytp-miniplayer-expand-watch-page-button");c?f=h=12:m?(b=g.gm(b,this.element),h=b.x,f=b.y-12):n&&(h=g.To(b,"ytp-miniplayer-button-top-left"),f=g.gm(b,this.element),b=g.im(b),h?(h=8,f=f.y+40):(h=f.x-l.width+b.width,f=f.y-20))}else h=c-l.width/2,d=25+(e||0);b=this.player.Wa().getPlayerSize().width;e=f+(e||0);l=g.Mg(h,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.k.showControls=function(){};
g.k.Im=function(){};
g.k.Wl=function(){return!1};g.w(J3,g.lJ);J3.prototype.create=function(){};
J3.prototype.bj=function(){return!1};
J3.prototype.load=function(){this.player.hideControls();this.j.show()};
J3.prototype.unload=function(){this.player.showControls();this.j.hide()};g.kJ("miniplayer",J3);})(_yt_player);
