/* ==UserStyle==
@name           Darling in The FranXX Logo
@namespace      USO Archive
@author         Zehnper
@description    `a dfranx backround`
@version        20201030.23.7
@license        NO-REDISTRIBUTION
@preprocessor   uso
==/UserStyle== */
@-moz-document domain("discord.com")
{
/* ------BACKGROUND------ */   /*contact me (FeaR#3500)*/
  body
  {
    background: url("https://www.teahub.io/photos/full/99-992172_darling-in-the-franxx-full-hd-1080p-60.png");
           /*artist https://www.pinterest.co.kr*/
    background-size: cover;
  }

  .appMount-3lHmkl
  {
    background: rgba(0, 0, 0, .6);
  }

/* ------REMOVE GREY/WHITE BG COLORS------ */
  .theme-dark,
.theme-light
  {
    --header-primary: #fff;
    --text-link: #f40000;
    --header-secondary: #00fff1;
    --text-normal: #dcddde;
    --text-muted: #38c3ee;
    --channels-default: #0298dc;
    --interactive-normal: #00dfff;
    --interactive-hover: #0080ff;
    --interactive-active: #00d9ff;
    --interactive-muted: #7a7a7a;
    --background-primary: transparent;
    --background-secondary: transparent;
    --background-tertiary: transparent;
    --background-accent: transparent;
    --background-floating: rgba(0, 0, 0, .8);
    --channeltextarea-background: #00ddff14;
    --activity-card-background: transparent;
    --deprecated-panel-background: transparent;
  }

/*remove borders*/
  .header-2o-2hj,
.searchBar-6Kv8R2,
.content-yTz4x3::before
  {
    box-shadow: none !important;
  }

/*misc*/
  .container-3gCOGc,  /*friends list*/
.wrapper-3WhCwL,    /*mentions*/
.scrollbar-2rkZSL,  /*scrollbar*/
.pad-29zQak,
.track-1JN30G
  {
    background: transparent !important;
  }

  .scrollbar-2rkZSL
  {
    width: 8px;
  }
/* ------SCROLLBAR------ */
  .theme-dark .scrollerThemed-2oenus.themedWithTrack-q8E3vB .scroller-2FKFPG::-webkit-scrollbar-track-piece
  {
    background-color: #00000036;
    border: 3px solid #08173000;
  }

  .theme-dark .scrollerThemed-2oenus.themedWithTrack-q8E3vB .scroller-2FKFPG::-webkit-scrollbar-thumb
  {
    background-color: #00f2ff6e;
    border-color: #00f2ff6e;
  }

  .thumb-2JwNFC
  {
    background: rgba(0, 0, 0, .5) !important;
  }

  .track-1JN30G,
.thumb-2JwNFC
  {
    border: none !important;
  }

/* ------EMBEDDED TEXT------ */
  .embedProvider-3k5pfl,
.embedDescription-1Cuq9a,
.embedFields-2IPs5Z,
.embedAuthorName-3mnTWj,
.embedFooterText-28V_Wb
  {
    color: #f2f2f2 !important;
  }

/* ------POP-UP------ */
  .modal-yWgWj-,
.footer-3rDWdC
  {
    background: rgba(0, 0, 0, .5) !important;
  }

/*BACKGROUND of PEOPLE*/
  .theme-dark .container-1D34oG
  {
    background-color: #36393f00;
  }
/*NITRO BACKGROUND*/
  .applicationStore-1pNvnv
  {
    background-color: #02020200;
  }

/*MENTION*/
  .theme-dark .wrapper-3UweLa
  {
    background: #21355200;
  }

  .theme-dark .wrapper-3UweLa
  {
    color: #b9bbbe;
    background: #20222500;
  }

  .theme-dark .header-ykumBX
  {
    background-color: #ff000000;
  }

  .theme-dark .messagesPopout-24nkyi
  {
    background-color: #00000029;
  }

  .theme-dark .messagesPopoutWrap-1MQ1bW
  {
    background-color: #040405b3;
    border: 1px solid rgba(58, 241, 252, 0.56);
    -webkit-box-shadow: 0 2px 10px 0 rgba(197, 12, 12, 0);
    box-shadow: 0 2px 10px 0 rgb(0, 241, 255);
  }

  .theme-dark .messageGroupWrapper-o-Zw7G
  {
    border-color: rgb(11, 179, 185);
    background-color: #000000bf;
  }

  .statusGreen-168O6Q
  {
    color: #00d5ff;
  }
/* NOW PLAYING */
  .theme-dark .jumpButton-3DTcS_
  {
    background-color: #b90b33cc;
  }

  .theme-dark .popoutContainer-3WC9HR:hover
  {
    background-color: #00000070;
  }

  .theme-dark .inset-GQDQYw
  {
    background-color: #3af0fb1a;
  }

  .theme-dark .popout-3G62UL
  {
    background-color: #040405c2;
  }

  .theme-dark .recentlyPlayedContainer-2F3MqS
  {
    background-color: #3af0fb1a;
  }

  .theme-dark .separator-2c4hi3
  {
    background-color: #00f0ff42;
  }

  .theme-dark .applicationStreamingPreviewWrapper-GnrvWN
  {
    background-color: #292b2f00;
  }

  .selected-aXhQR6 .layout-2DM8Md
  {
    background-color: #41f1fc4f;
  }

/*active channels*/
  .modeConnected-2IEL4z .name-3_Dsmg, .modeConnected-2IEL4z:hover .name-3_Dsmg, .modeSelected-1zApJ_ .name-3_Dsmg, .modeSelected-1zApJ_:hover .name-3_Dsmg, .modeUnread-1zpFdA .name-3_Dsmg, .modeUnread-1zpFdA:hover .name-3_Dsmg, .notInteractive-YF5EXq.modeConnected-2IEL4z .name-3_Dsmg, .notInteractive-YF5EXq.modeSelected-1zApJ_ .name-3_Dsmg
  {
    color: #00fff3;
  }

/*default nicknames8*/
  .container-2Pjhx-
  {
    color: #ffffff;
  }

  .activity-2Gy-9S
  {
    color: #c7c7c7;
  }
/*UPLOAD FILE*/
  .theme-dark .uploadModal-2ifh8j
  {
    background-color: #0000006b;
    -webkit-box-shadow: 0 0 0 1px rgba(16, 52, 105, 0.86), 0 2px 10px 0 rgba(255, 6, 6, 0);
    box-shadow: 0 0 0 1px rgba(3, 169, 244, 0.12), 0 2px 10px 0 rgb(3, 169, 244);
  }

  .theme-dark .footer-3mqk7D
  {
    background-color: #0000006b;
    -webkit-box-shadow: inset 0 1px 0 rgba(255, 0, 0, 0.54);
    box-shadow: inset 0 1px 0 rgba(3, 169, 244, 0.6);
  }
  /*UPLOAD BUTTON*/
  .lookFilled-1Gx00P.colorBrand-3pXr91
  {
    background-color: #03a9f4c9;
  }

  .lookFilled-1Gx00P.colorBrand-3pXr91:hover
  {
    background-color: #f40303;
  }
/*GIFS*/
  .theme-dark .autocomplete-1vrmpx
  {
    background-color: #000000a3;
  }
 /*NITRO GIFT*/
  .theme-dark .root-1gCeng
  {
    background-color: #000000cc;
    -webkit-box-shadow: 0 0 0 1px rgba(32,34,37,.6), 0 2px 10px 0 rgba(0,0,0,.2);
    box-shadow: 0 0 0 1px rgba(3, 169, 244, 0.34), 0 2px 10px 0 #03A9F4;
  }
/*search*/
  .theme-dark .searchResultsWrap-2DKFzt
  {
    background-color: #00000096;
  }

  .theme-dark .searchHeader-1l-wpR
  {
    background-color: #000000c2;
  }

  .theme-dark .searchResultsWrap-2DKFzt
  {
    background-color: #00000000;
  }

  .theme-dark .searchResult-3pzFAB .hit-NLlWXA
  {
    background-color: #00000061;
    -webkit-box-shadow: 0 0 10px 6px #2f313600;
    box-shadow: 0 0 10px 6px #0000004a;
  }

  .theme-dark .channelSeparator-1X1FuH .channelName-1QajIf
  {
    color: #fff;
    background-color: #2f313600;
  }

  .theme-dark .searchResult-3pzFAB:before
  {
    background-image: -webkit-gradient(linear,left bottom,left top,from(rgba(47,49,54,0)),to(#2f313600));
    background-image: linear-gradient(0deg,rgba(47,49,54,0),#000000bd);
  }

  .theme-dark .searchResult-3pzFAB:after
  {
    background-image: -webkit-gradient(linear,left bottom,left top,from(rgba(47,49,54,0)),to(#2f313600));
    background-image: linear-gradient(0deg,rgba(47,49,54,0),#000000bd);
  }
/*PEOPLE friends list shadow object selection*/
  .peopleListItem-2nzedh:hover
  {
    background: #0000005e;
  }

  .clickable-1JJAn8:hover .layout-2DM8Md
  {
    background-color: rgba(0, 0, 0, 0.26);
  }

  .wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9, .wrapper-1BJsBx:hover .childWrapper-anI2G9
  {
  /*SELECTED CHANNEL*/
    color: #fff;
    background-color: #00caffbf;
  }

/*EVERYONEEEEEEEEEEEEEEEEE*/
  .theme-dark .isMentioned-N-h9aa
  {
    background: rgba(233, 30, 99, 0.19);
  }

  .isMentionedCozy-3isp7y:after
  {
    background: #E91E63;
    border-left: 4px solid #E91E63;
  }

  .theme-dark .wrapper-3WhCwL
  {
    color: #03ff3a;
  }

  .reaction-1ELvT8.reactionMe-23mbRf
  {
    background-color: rgba(233, 30, 99, 0.25);
  }

/*emoji*/
  .emojiPicker-3m1S-j
  {
    overflow: hidden;
    background-color: #000000b3;
    box-shadow: 0 0 10px #00fffb;
  }

  .infoBar-U6oBFk
  {
    background-color: #0000;
  }
/* deleting message*/
  .theme-dark .message-2qRu38
  {
    background-color: #000000b8;
  }

  .lookFilled-1Gx00P.colorRed-1TFJan
  {
    color: #fff;
    background-color: #00f2ff;
  }

  .modeSelected-1zApJ_ .content-3at_AU, .modeSelected-1zApJ_:hover .content-3at_AU
  {
    background-color: #41f1fc4f;
  }

  .wrapper-1ucjTd:hover .content-3at_AU
  {
    background-color: rgba(0, 0, 0, 0.52);
  }

  .theme-dark .pageWrapper-1PgVDX
  {
    background-color: #0000001f;
    color: #fff;
  }

  .theme-dark .searchBox-3Y2Vi7
  {
    background-color: #000000cc;
  }

  .theme-dark .card-3DjzTQ, .theme-dark .cardPlaceholder-1zrbbe
  {
    background: #000000;
  }

  .botTagRegular-2HEhHi
  {
    background: #0014ff;
  }
/*USER PROF*/
  .theme-dark .headerNormal-T_seeN
  {
    background-color: #000000c2;
  }

  .theme-dark .bodyInner-245q0L, .theme-dark .footer-1fjuF6
  {
    background-color: #000000c2;
  }

  .theme-dark .quickMessage-1yeL4E
  {
    background-color: #000000;
    border-color: #03a9f4;
  }

  .userPopout-3XzG_A
  {
    box-shadow: 0 2px 10px 0 #03A9F4, 0 0 0 1px #03A9F4;
  }

  .headerPlaying-j0WQBV, .headerStreaming-2FjmGz
  {
    background: #000000c2;
  }

  .activity-11LB_k
  {
    background-color: rgba(3, 169, 244, 0.1);
  }

  .theme-dark .bodyInner-245q0L, .theme-dark .footer-1fjuF6
  {
    color: hsl(0, 0%, 100%);
  }
/*USER CALL*/
  .theme-dark .wrapper-29NfPK
  {
    background-color: #00000087;
  }

  .theme-dark .wrapper-29NfPK.minimum-2d6zH6 .actions-2vadYq .center-1Vp33r
  {
    border-color: #03a9f41a;
    background-color: #00000000;
  }

  .topSectionPlaying-1J5E4n
  {
    background: #7289da00;
  }


/*SEARCH OPTIONS*/
  .theme-dark .container-3ayLPN
  {
    background-color: #091833;
  }

  .theme-dark .elevationBorderHigh-2WYJ09
  {
    -webkit-box-shadow: 0 0 0 1px rgba(10, 189, 198,.6), 0 2px 10px 0 rgba(0,0,0,.2);
    box-shadow: 0 0 0 1px rgba(10, 189, 198,.6), 0 2px 10px 0 rgba(0,0,0,.2);
  }

  .theme-dark .resultsGroup-r_nuzN .header-2N-gMV, .theme-dark .resultsGroup-r_nuzN .plusIcon-v0BTrL, .theme-dark .resultsGroup-r_nuzN .searchClearHistory-2cSSMO, .theme-dark .resultsGroup-r_nuzN .searchLearnMore-3SQUAj a
  {
    color: #0abdc6;
  }

  .theme-dark .searchOption-zQ-1l6 .filter-3Y_im-
  {
    color: #0ac668;
  }

  .theme-dark .searchOption-zQ-1l6 .answer-1n6g43
  {
    color: rgba(10, 189, 198, 0.5);
  }

  .theme-dark .resultsGroup-r_nuzN .header-2N-gMV, .theme-dark .resultsGroup-r_nuzN .plusIcon-v0BTrL, .theme-dark .resultsGroup-r_nuzN .searchClearHistory-2cSSMO, .theme-dark .resultsGroup-r_nuzN .searchLearnMore-3SQUAj a
  {
    color: #0abdc6;
  }

  .theme-dark .resultsGroup-r_nuzN:hover .header-2N-gMV:hover, .theme-dark .resultsGroup-r_nuzN:hover .plusIcon-v0BTrL:hover, .theme-dark .resultsGroup-r_nuzN:hover .searchClearHistory-2cSSMO:hover, .theme-dark .resultsGroup-r_nuzN:hover .searchLearnMore-3SQUAj:hover a
  {
    color: #00ea79;
  }

  .theme-dark .option-96V44q:after
  {
    background: none;
  }

  .theme-dark .option-96V44q .answer-1n6g43, .theme-dark .option-96V44q .nonText-3CRkO0, .theme-dark .option-96V44q strong
  {
    color: #00e2ea;
  }

  .theme-dark .option-96V44q.selected-rZcOL-
  {
    background-color: rgba(19, 115, 124, .6);
  }

  .theme-dark .option-96V44q.selected-rZcOL-:after
  {
    background: none;
  }

  .theme-dark .focused-2bY0OD
  {
    background-color: #000b1e;
  }

  .theme-dark .queryContainer-RKFJW-
  {
    color: #0abdc6;
    border-bottom-color: rgba(19, 62, 124,.3);
  }

  .theme-dark .queryContainer-RKFJW- strong
  {
    color: #00c7ea;
  }

  .theme-dark .option-96V44q .filter-3Y_im-
  {
    color: rgba(10, 189, 198, .7);
  }

  .theme-dark .dim-1l4L4y span
  {
    background-color: #133e7c;
    color: #0abdc6;
  }

  .theme-dark .keybindShortcut-1BD6Z1 span
  {
    color: #0abdc6;
    -webkit-box-shadow: inset 0 -4px 0 rgba(0, 29, 30, .6);
    box-shadow: inset 0 -4px 0 rgba(0, 24, 30, .6);
    border: 1px solid #092e33;
    background-color: #13697c;
  }
/*FOLLOW 2*/
  .theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6
  {
    color: #f6f6f7;
    background-color: #00f2ff;
  }

  .dividerEnabled-2TTlcf
  {
    border-bottom-color: hsla(184, 100%, 50%, .06);
  }

  .form-2fGMdU
  {
    border-top: 1px solid hsla(181, 100%, 50%, .06);
    -ms-flex-negative: 0;
    flex-shrink: 0;
    margin-left: 20px;
    margin-right: 20px;
  }

  .newMessagesBar-mujexs
  {
    top: 0;
    border-radius: 0 0 8px 8px;
    background-color: #f90000;
    -webkit-box-shadow: var(--elevation-low);
    box-shadow: var(--elevation-low);
  }

  .scrollableContainer-2NUZem
  {
    border-radius: 30px;
  }
/*Main user panel*/
  .panels-j1Uci_
  {
    background-color: #292b2f00;
  }
/*ACTIVE NOW*/
  .theme-dark .inset-3sAvek
  {
    background-color: #ff000000;
  }

  .theme-dark .popout-13LQ_3
  {
    background-color: #00000066;
  }
/*active now selected*/
  .theme-dark .popout-38lTFE
  {
    background-color: #000000a6;
    -webkit-box-shadow: 0px 0px 0px 1px rgb(0, 225, 255);
    box-shadow: 0px 0px 20px rgb(0, 255, 255);
  }

  .theme-dark .outer-1AjyKL.active-1xchHY, .theme-dark .outer-1AjyKL.interactive-3B9GmY:hover
  {
    background-color: #000000a6;
    -webkit-box-shadow: 0px 0px 0px 1px rgb(0, 251, 255);
    box-shadow: 0px 0px 20px rgb(0, 229, 255);
  }
/*Main user panel*/
  .panels-j1Uci_
  {
    background-color: #292b2f00;
  }
/*on botton*/
  .themeDefault-24hCdX.valueChecked-m-4IJZ
  {
    background-color: #ff0000;
  }

  element.style
  {
    border-color: rgb(255, 0, 0);
    background-color: rgb(255, 0, 0);
    box-shadow: 0 0 20px red;
  }
/*clicked reaction*/
  .reaction-1hd86g.reactionMe-wv5HKu
  {
    background-color: rgba(255, 0, 0, 0.3);
  }
/*new mentions*/
  .mention-1f5kbO
  {
    background-color: #f40303;
  }
/*pinned messagers*/
  .iconBadge-qZ4Ksk
  {
    background-color: #f40303;
  }
/*addressed you*/
  .mentioned-xhSam7
  {
    background-color: rgba(244, 3, 3, .12);
  }

  .mentioned-xhSam7:before
  {
    background-color: #f40303;
  }
/*1.2*/
/*discord player*/
  .mediaBarGrabber-1FqnbN, .mediaBarProgress-1xaPtl, .mediaBarProgress-1xaPtl:after, .mediaBarProgress-1xaPtl:before
  {
    background-color: #0ef;
  }
/*discord audio player*/
  .theme-dark .wrapperAudio-1jDe0Q
  {
    background-color: rgba(0, 97, 99, .3);
    border-color: rgba(0, 208, 255, .62);
  }
}
