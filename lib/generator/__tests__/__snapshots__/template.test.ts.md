# Snapshot report for `lib/generator/__tests__/template.test.ts`

The actual snapshot is saved in `template.test.ts.snap`.

Generated by [AVA](https://avajs.dev).

## quantumultx filter 2

> Snapshot 1

    `# RULE 1␊
    ^https?://m?api\\.weibo\\.c(n|om)/2/(statuses/(unread|extend|positives/get|(friends|video)(/|_)timeline)|stories/(video_stream|home_list)|(groups|fangle)/timeline|profile/statuses|comments/build_comments|photo/recommend_list|service/picfeed|searchall|cardlist|page|\\!/photos/pic_recommend_status) url script-response-body https://raw.githubusercontent.com/yichahucha/surge/master/wb_ad.js␊
    ^https?://(sdk|wb)app\\.uve\\.weibo\\.com(/interface/sdk/sdkad.php|/wbapplua/wbpullad.lua) url script-response-body https://raw.githubusercontent.com/yichahucha/surge/master/wb_launch.js␊
    # RULE 2␊
    https://api.zhihu.com/moments\\?(action|feed_type) url script-response-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20feed.js␊
    https://api.zhihu.com/topstory/recommend url script-response-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20recommend.js␊
    https://api.zhihu.com/.*/questions url script-response-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20answer.js␊
    https://api.zhihu.com/market/header url script-response-header https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20market.js␊
    https://api.zhihu.com/people/ url script-response-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20people.js␊
    https://api.zhihu.com/.*/questions url script-request-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20answer.js␊
    https://api.zhihu.com/market/header url script-request-header https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20market.js␊
    # RULE 3␊
    # RULE 4␊
    https://api.zhihu.com/people/ url script-response-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20people.js␊
    https://api.zhihu.com/moments/recommend url script-response-header https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20feed.js␊
    https://api.zhihu.com/topstory/recommend url script-request-body https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20recommend.js␊
    https://api.zhihu.com/v4/questions url script-request-header https://raw.githubusercontent.com/onewayticket255/Surge-Script/master/surge%20zhihu%20answer.js`

## ForeignMedia

> Snapshot 1

    `# (ForeignMedia)␊
    # (Music)␊
    # > Deezer␊
    USER-AGENT,Deezer*␊
    DOMAIN-SUFFIX,deezer.com␊
    DOMAIN-SUFFIX,dzcdn.net␊
    # > KKBOX␊
    DOMAIN-SUFFIX,kkbox.com␊
    DOMAIN-SUFFIX,kkbox.com.tw␊
    DOMAIN-SUFFIX,kfs.io␊
    # > JOOX␊
    USER-AGENT,WeMusic*␊
    USER-AGENT,JOOX*␊
    DOMAIN-SUFFIX,joox.com␊
    # > Pandora␊
    USER-AGENT,Pandora*␊
    DOMAIN-SUFFIX,pandora.com␊
    # > SoundCloud␊
    USER-AGENT,SoundCloud*␊
    DOMAIN-SUFFIX,p-cdn.us␊
    DOMAIN-SUFFIX,sndcdn.com␊
    DOMAIN-SUFFIX,soundcloud.com␊
    # > Spotify␊
    USER-AGENT,Spotify*␊
    DOMAIN-SUFFIX,pscdn.co␊
    DOMAIN-SUFFIX,scdn.co␊
    DOMAIN-SUFFIX,spotify.com␊
    DOMAIN-SUFFIX,spoti.fi␊
    # > TIDAL␊
    USER-AGENT,TIDAL*␊
    DOMAIN-SUFFIX,tidal.com␊
    # > YouTubeMusic␊
    USER-AGENT,com.google.ios.youtubemusic*␊
    USER-AGENT,YouTubeMusic*␊
    # (Video)␊
    # > All4␊
    USER-AGENT,All4*␊
    DOMAIN-SUFFIX,c4assets.com␊
    DOMAIN-SUFFIX,channel4.com␊
    # > AbemaTV␊
    USER-AGENT,AbemaTV*␊
    DOMAIN-SUFFIX,abema.io␊
    DOMAIN-SUFFIX,ameba.jp␊
    DOMAIN-SUFFIX,abema.tv␊
    DOMAIN-SUFFIX,hayabusa.io␊
    DOMAIN,abematv.akamaized.net␊
    DOMAIN,ds-linear-abematv.akamaized.net␊
    DOMAIN,ds-vod-abematv.akamaized.net␊
    DOMAIN,linear-abematv.akamaized.net␊
    # > Amazon Prime Video␊
    USER-AGENT,InstantVideo.US*␊
    USER-AGENT,Prime%20Video*␊
    DOMAIN-SUFFIX,aiv-cdn.net␊
    DOMAIN-SUFFIX,aiv-delivery.net␊
    DOMAIN-SUFFIX,amazonvideo.com␊
    DOMAIN-SUFFIX,media-amazon.com␊
    DOMAIN-SUFFIX,primevideo.com␊
    # > Bahamut␊
    USER-AGENT,Anime*␊
    DOMAIN-SUFFIX,bahamut.com.tw␊
    DOMAIN-SUFFIX,gamer.com.tw␊
    DOMAIN,gamer-cds.cdn.hinet.net␊
    DOMAIN,gamer2-cds.cdn.hinet.net␊
    # > BBC iPlayer␊
    USER-AGENT,BBCiPlayer*␊
    DOMAIN-SUFFIX,bbc.co.uk␊
    DOMAIN-SUFFIX,bbci.co.uk␊
    DOMAIN-KEYWORD,bbcfmt␊
    DOMAIN-KEYWORD,uk-live␊
    # > DAZN␊
    USER-AGENT,DAZN*␊
    DOMAIN-SUFFIX,dazn.com␊
    DOMAIN-SUFFIX,dazn-api.com␊
    DOMAIN,d151l6v8er5bdm.cloudfront.net␊
    DOMAIN-KEYWORD,voddazn␊
    # > Disney+␊
    USER-AGENT,Disney+*␊
    DOMAIN-SUFFIX,bamgrid.com␊
    DOMAIN-SUFFIX,disney-plus.net␊
    DOMAIN-SUFFIX,disneyplus.com␊
    DOMAIN-SUFFIX,dssott.com␊
    DOMAIN,cdn.registerdisney.go.com␊
    # > encoreTVB␊
    USER-AGENT,encoreTVB*␊
    DOMAIN-SUFFIX,encoretvb.com␊
    DOMAIN,edge.api.brightcove.com␊
    DOMAIN,bcbolt446c5271-a.akamaihd.net␊
    # > Fox+ & Fox Now␊
    USER-AGENT,FOX%20NOW*␊
    USER-AGENT,FOXPlus*␊
    DOMAIN-SUFFIX,dashasiafox.akamaized.net␊
    DOMAIN-SUFFIX,fox.com␊
    DOMAIN-SUFFIX,foxdcg.com␊
    DOMAIN-SUFFIX,foxplus.com␊
    DOMAIN-SUFFIX,staticasiafox.akamaized.net␊
    DOMAIN-SUFFIX,theplatform.com␊
    DOMAIN-SUFFIX,uplynk.com␊
    # > HBO Now & HBO GO␊
    USER-AGENT,HBO%20NOW*␊
    USER-AGENT,HBO%20GO*␊
    USER-AGENT,HBOAsia*␊
    DOMAIN-SUFFIX,hbo.com␊
    DOMAIN-SUFFIX,hbogo.com␊
    DOMAIN-SUFFIX,hboasia.com␊
    DOMAIN-SUFFIX,hbogo.com␊
    DOMAIN-SUFFIX,hbogoasia.hk␊
    DOMAIN,44wilhpljf.execute-api.ap-southeast-1.amazonaws.com␊
    DOMAIN,bcbolthboa-a.akamaihd.net␊
    DOMAIN,cf-images.ap-southeast-1.prod.boltdns.net␊
    DOMAIN,manifest.prod.boltdns.net␊
    DOMAIN,s3-ap-southeast-1.amazonaws.com␊
    # > 华文电视␊
    USER-AGENT,HWTVMobile*␊
    DOMAIN-SUFFIX,5itv.tv␊
    DOMAIN-SUFFIX,ocnttv.com␊
    # > Hulu␊
    DOMAIN-SUFFIX,hulu.com␊
    DOMAIN-SUFFIX,huluim.com␊
    DOMAIN-SUFFIX,hulustream.com␊
    # > Hulu(フールー)␊
    DOMAIN-SUFFIX,happyon.jp␊
    DOMAIN-SUFFIX,hulu.jp␊
    # > ITV␊
    USER-AGENT,ITV_Player*␊
    DOMAIN-SUFFIX,itv.com␊
    DOMAIN-SUFFIX,itvstatic.com␊
    DOMAIN,itvpnpmobile-a.akamaihd.net␊
    # > KKTV␊
    USER-AGENT,KKTV*␊
    USER-AGENT,com.kktv.ios.kktv*␊
    DOMAIN-SUFFIX,kktv.com.tw␊
    DOMAIN-SUFFIX,kktv.me␊
    DOMAIN,kktv-theater.kk.stream␊
    # > Line TV␊
    USER-AGENT,LINE%20TV*␊
    DOMAIN-SUFFIX,linetv.tw␊
    DOMAIN,d3c7rimkq79yfu.cloudfront.net␊
    # > LiTV␊
    DOMAIN-SUFFIX,litv.tv␊
    DOMAIN,litvfreemobile-hichannel.cdn.hinet.net␊
    # > My5␊
    USER-AGENT,My5*␊
    DOMAIN-SUFFIX,channel5.com␊
    DOMAIN-SUFFIX,my5.tv␊
    DOMAIN,d349g9zuie06uo.cloudfront.net␊
    # > myTV SUPER␊
    USER-AGENT,mytv*␊
    DOMAIN-SUFFIX,mytvsuper.com␊
    DOMAIN-SUFFIX,tvb.com␊
    # > Netflix␊
    USER-AGENT,Argo*␊
    DOMAIN-SUFFIX,netflix.com␊
    DOMAIN-SUFFIX,netflix.net␊
    DOMAIN-SUFFIX,nflxext.com␊
    DOMAIN-SUFFIX,nflximg.com␊
    DOMAIN-SUFFIX,nflximg.net␊
    DOMAIN-SUFFIX,nflxso.net␊
    DOMAIN-SUFFIX,nflxvideo.net␊
    IP-CIDR,23.246.0.0/18,no-resolve␊
    IP-CIDR,37.77.184.0/21,no-resolve␊
    IP-CIDR,45.57.0.0/17,no-resolve␊
    IP-CIDR,64.120.128.0/17,no-resolve␊
    IP-CIDR,66.197.128.0/17,no-resolve␊
    IP-CIDR,108.175.32.0/20,no-resolve␊
    IP-CIDR,192.173.64.0/18,no-resolve␊
    IP-CIDR,198.38.96.0/19,no-resolve␊
    IP-CIDR,198.45.48.0/20,no-resolve␊
    # > niconico␊
    USER-AGENT,Niconico*␊
    DOMAIN-SUFFIX,dmc.nico␊
    DOMAIN-SUFFIX,nicovideo.jp␊
    DOMAIN-SUFFIX,nimg.jp␊
    DOMAIN-SUFFIX,socdm.com␊
    # > PBS␊
    USER-AGENT,PBS*␊
    DOMAIN-SUFFIX,pbs.org␊
    # > Pornhub␊
    DOMAIN-SUFFIX,phncdn.com␊
    DOMAIN-SUFFIX,pornhub.com␊
    DOMAIN-SUFFIX,pornhubpremium.com␊
    # > 台湾好␊
    USER-AGENT,TaiwanGood*␊
    DOMAIN-SUFFIX,skyking.com.tw␊
    DOMAIN,hamifans.emome.net␊
    # > Twitch␊
    DOMAIN-SUFFIX,twitch.tv␊
    DOMAIN-SUFFIX,twitchcdn.net␊
    DOMAIN-SUFFIX,ttvnw.net␊
    # > ViuTV␊
    USER-AGENT,Viu*␊
    USER-AGENT,ViuTV*␊
    DOMAIN-SUFFIX,viu.com␊
    DOMAIN-SUFFIX,viu.tv␊
    DOMAIN,api.viu.now.com␊
    DOMAIN,d1k2us671qcoau.cloudfront.net␊
    DOMAIN,d2anahhhmp1ffz.cloudfront.net␊
    DOMAIN,dfp6rglgjqszk.cloudfront.net␊
    # > YouTube␊
    USER-AGENT,com.google.ios.youtube*␊
    USER-AGENT,YouTube*␊
    DOMAIN-SUFFIX,googlevideo.com␊
    DOMAIN-SUFFIX,youtube.com␊
    DOMAIN,youtubei.googleapis.com`

> Snapshot 2

    `# (ForeignMedia)␊
    # (Music)␊
    # > Deezer␊
    - DOMAIN-SUFFIX,deezer.com␊
    - DOMAIN-SUFFIX,dzcdn.net␊
    # > KKBOX␊
    - DOMAIN-SUFFIX,kkbox.com␊
    - DOMAIN-SUFFIX,kkbox.com.tw␊
    - DOMAIN-SUFFIX,kfs.io␊
    # > JOOX␊
    - DOMAIN-SUFFIX,joox.com␊
    # > Pandora␊
    - DOMAIN-SUFFIX,pandora.com␊
    # > SoundCloud␊
    - DOMAIN-SUFFIX,p-cdn.us␊
    - DOMAIN-SUFFIX,sndcdn.com␊
    - DOMAIN-SUFFIX,soundcloud.com␊
    # > Spotify␊
    - DOMAIN-SUFFIX,pscdn.co␊
    - DOMAIN-SUFFIX,scdn.co␊
    - DOMAIN-SUFFIX,spotify.com␊
    - DOMAIN-SUFFIX,spoti.fi␊
    # > TIDAL␊
    - DOMAIN-SUFFIX,tidal.com␊
    # > YouTubeMusic␊
    # (Video)␊
    # > All4␊
    - DOMAIN-SUFFIX,c4assets.com␊
    - DOMAIN-SUFFIX,channel4.com␊
    # > AbemaTV␊
    - DOMAIN-SUFFIX,abema.io␊
    - DOMAIN-SUFFIX,ameba.jp␊
    - DOMAIN-SUFFIX,abema.tv␊
    - DOMAIN-SUFFIX,hayabusa.io␊
    - DOMAIN,abematv.akamaized.net␊
    - DOMAIN,ds-linear-abematv.akamaized.net␊
    - DOMAIN,ds-vod-abematv.akamaized.net␊
    - DOMAIN,linear-abematv.akamaized.net␊
    # > Amazon Prime Video␊
    - DOMAIN-SUFFIX,aiv-cdn.net␊
    - DOMAIN-SUFFIX,aiv-delivery.net␊
    - DOMAIN-SUFFIX,amazonvideo.com␊
    - DOMAIN-SUFFIX,media-amazon.com␊
    - DOMAIN-SUFFIX,primevideo.com␊
    # > Bahamut␊
    - DOMAIN-SUFFIX,bahamut.com.tw␊
    - DOMAIN-SUFFIX,gamer.com.tw␊
    - DOMAIN,gamer-cds.cdn.hinet.net␊
    - DOMAIN,gamer2-cds.cdn.hinet.net␊
    # > BBC iPlayer␊
    - DOMAIN-SUFFIX,bbc.co.uk␊
    - DOMAIN-SUFFIX,bbci.co.uk␊
    - DOMAIN-KEYWORD,bbcfmt␊
    - DOMAIN-KEYWORD,uk-live␊
    # > DAZN␊
    - DOMAIN-SUFFIX,dazn.com␊
    - DOMAIN-SUFFIX,dazn-api.com␊
    - DOMAIN,d151l6v8er5bdm.cloudfront.net␊
    - DOMAIN-KEYWORD,voddazn␊
    # > Disney+␊
    - DOMAIN-SUFFIX,bamgrid.com␊
    - DOMAIN-SUFFIX,disney-plus.net␊
    - DOMAIN-SUFFIX,disneyplus.com␊
    - DOMAIN-SUFFIX,dssott.com␊
    - DOMAIN,cdn.registerdisney.go.com␊
    # > encoreTVB␊
    - DOMAIN-SUFFIX,encoretvb.com␊
    - DOMAIN,edge.api.brightcove.com␊
    - DOMAIN,bcbolt446c5271-a.akamaihd.net␊
    # > Fox+ & Fox Now␊
    - DOMAIN-SUFFIX,dashasiafox.akamaized.net␊
    - DOMAIN-SUFFIX,fox.com␊
    - DOMAIN-SUFFIX,foxdcg.com␊
    - DOMAIN-SUFFIX,foxplus.com␊
    - DOMAIN-SUFFIX,staticasiafox.akamaized.net␊
    - DOMAIN-SUFFIX,theplatform.com␊
    - DOMAIN-SUFFIX,uplynk.com␊
    # > HBO Now & HBO GO␊
    - DOMAIN-SUFFIX,hbo.com␊
    - DOMAIN-SUFFIX,hbogo.com␊
    - DOMAIN-SUFFIX,hboasia.com␊
    - DOMAIN-SUFFIX,hbogo.com␊
    - DOMAIN-SUFFIX,hbogoasia.hk␊
    - DOMAIN,44wilhpljf.execute-api.ap-southeast-1.amazonaws.com␊
    - DOMAIN,bcbolthboa-a.akamaihd.net␊
    - DOMAIN,cf-images.ap-southeast-1.prod.boltdns.net␊
    - DOMAIN,manifest.prod.boltdns.net␊
    - DOMAIN,s3-ap-southeast-1.amazonaws.com␊
    # > 华文电视␊
    - DOMAIN-SUFFIX,5itv.tv␊
    - DOMAIN-SUFFIX,ocnttv.com␊
    # > Hulu␊
    - DOMAIN-SUFFIX,hulu.com␊
    - DOMAIN-SUFFIX,huluim.com␊
    - DOMAIN-SUFFIX,hulustream.com␊
    # > Hulu(フールー)␊
    - DOMAIN-SUFFIX,happyon.jp␊
    - DOMAIN-SUFFIX,hulu.jp␊
    # > ITV␊
    - DOMAIN-SUFFIX,itv.com␊
    - DOMAIN-SUFFIX,itvstatic.com␊
    - DOMAIN,itvpnpmobile-a.akamaihd.net␊
    # > KKTV␊
    - DOMAIN-SUFFIX,kktv.com.tw␊
    - DOMAIN-SUFFIX,kktv.me␊
    - DOMAIN,kktv-theater.kk.stream␊
    # > Line TV␊
    - DOMAIN-SUFFIX,linetv.tw␊
    - DOMAIN,d3c7rimkq79yfu.cloudfront.net␊
    # > LiTV␊
    - DOMAIN-SUFFIX,litv.tv␊
    - DOMAIN,litvfreemobile-hichannel.cdn.hinet.net␊
    # > My5␊
    - DOMAIN-SUFFIX,channel5.com␊
    - DOMAIN-SUFFIX,my5.tv␊
    - DOMAIN,d349g9zuie06uo.cloudfront.net␊
    # > myTV SUPER␊
    - DOMAIN-SUFFIX,mytvsuper.com␊
    - DOMAIN-SUFFIX,tvb.com␊
    # > Netflix␊
    - DOMAIN-SUFFIX,netflix.com␊
    - DOMAIN-SUFFIX,netflix.net␊
    - DOMAIN-SUFFIX,nflxext.com␊
    - DOMAIN-SUFFIX,nflximg.com␊
    - DOMAIN-SUFFIX,nflximg.net␊
    - DOMAIN-SUFFIX,nflxso.net␊
    - DOMAIN-SUFFIX,nflxvideo.net␊
    - IP-CIDR,23.246.0.0/18,no-resolve␊
    - IP-CIDR,37.77.184.0/21,no-resolve␊
    - IP-CIDR,45.57.0.0/17,no-resolve␊
    - IP-CIDR,64.120.128.0/17,no-resolve␊
    - IP-CIDR,66.197.128.0/17,no-resolve␊
    - IP-CIDR,108.175.32.0/20,no-resolve␊
    - IP-CIDR,192.173.64.0/18,no-resolve␊
    - IP-CIDR,198.38.96.0/19,no-resolve␊
    - IP-CIDR,198.45.48.0/20,no-resolve␊
    # > niconico␊
    - DOMAIN-SUFFIX,dmc.nico␊
    - DOMAIN-SUFFIX,nicovideo.jp␊
    - DOMAIN-SUFFIX,nimg.jp␊
    - DOMAIN-SUFFIX,socdm.com␊
    # > PBS␊
    - DOMAIN-SUFFIX,pbs.org␊
    # > Pornhub␊
    - DOMAIN-SUFFIX,phncdn.com␊
    - DOMAIN-SUFFIX,pornhub.com␊
    - DOMAIN-SUFFIX,pornhubpremium.com␊
    # > 台湾好␊
    - DOMAIN-SUFFIX,skyking.com.tw␊
    - DOMAIN,hamifans.emome.net␊
    # > Twitch␊
    - DOMAIN-SUFFIX,twitch.tv␊
    - DOMAIN-SUFFIX,twitchcdn.net␊
    - DOMAIN-SUFFIX,ttvnw.net␊
    # > ViuTV␊
    - DOMAIN-SUFFIX,viu.com␊
    - DOMAIN-SUFFIX,viu.tv␊
    - DOMAIN,api.viu.now.com␊
    - DOMAIN,d1k2us671qcoau.cloudfront.net␊
    - DOMAIN,d2anahhhmp1ffz.cloudfront.net␊
    - DOMAIN,dfp6rglgjqszk.cloudfront.net␊
    # > YouTube␊
    - DOMAIN-SUFFIX,googlevideo.com␊
    - DOMAIN-SUFFIX,youtube.com␊
    - DOMAIN,youtubei.googleapis.com`

> Snapshot 3

    `# (ForeignMedia)␊
    # (Music)␊
    # > Deezer␊
    DOMAIN-SUFFIX,deezer.com␊
    DOMAIN-SUFFIX,dzcdn.net␊
    ␊
    # > KKBOX␊
    DOMAIN-SUFFIX,kkbox.com␊
    DOMAIN-SUFFIX,kkbox.com.tw␊
    DOMAIN-SUFFIX,kfs.io␊
    ␊
    # > JOOX␊
    DOMAIN-SUFFIX,joox.com␊
    ␊
    # > Pandora␊
    DOMAIN-SUFFIX,pandora.com␊
    ␊
    # > SoundCloud␊
    DOMAIN-SUFFIX,p-cdn.us␊
    DOMAIN-SUFFIX,sndcdn.com␊
    DOMAIN-SUFFIX,soundcloud.com␊
    ␊
    # > Spotify␊
    DOMAIN-SUFFIX,pscdn.co␊
    DOMAIN-SUFFIX,scdn.co␊
    DOMAIN-SUFFIX,spotify.com␊
    DOMAIN-SUFFIX,spoti.fi␊
    ␊
    # > TIDAL␊
    DOMAIN-SUFFIX,tidal.com␊
    ␊
    # > YouTubeMusic␊
    ␊
    # (Video)␊
    # > All4␊
    DOMAIN-SUFFIX,c4assets.com␊
    DOMAIN-SUFFIX,channel4.com␊
    ␊
    # > AbemaTV␊
    DOMAIN-SUFFIX,abema.io␊
    DOMAIN-SUFFIX,ameba.jp␊
    DOMAIN-SUFFIX,abema.tv␊
    DOMAIN-SUFFIX,hayabusa.io␊
    DOMAIN,abematv.akamaized.net␊
    DOMAIN,ds-linear-abematv.akamaized.net␊
    DOMAIN,ds-vod-abematv.akamaized.net␊
    DOMAIN,linear-abematv.akamaized.net␊
    ␊
    # > Amazon Prime Video␊
    DOMAIN-SUFFIX,aiv-cdn.net␊
    DOMAIN-SUFFIX,aiv-delivery.net␊
    DOMAIN-SUFFIX,amazonvideo.com␊
    DOMAIN-SUFFIX,media-amazon.com␊
    DOMAIN-SUFFIX,primevideo.com␊
    ␊
    # > Bahamut␊
    DOMAIN-SUFFIX,bahamut.com.tw␊
    DOMAIN-SUFFIX,gamer.com.tw␊
    DOMAIN,gamer-cds.cdn.hinet.net␊
    DOMAIN,gamer2-cds.cdn.hinet.net␊
    ␊
    # > BBC iPlayer␊
    DOMAIN-SUFFIX,bbc.co.uk␊
    DOMAIN-SUFFIX,bbci.co.uk␊
    DOMAIN-KEYWORD,bbcfmt␊
    DOMAIN-KEYWORD,uk-live␊
    ␊
    # > DAZN␊
    DOMAIN-SUFFIX,dazn.com␊
    DOMAIN-SUFFIX,dazn-api.com␊
    DOMAIN,d151l6v8er5bdm.cloudfront.net␊
    DOMAIN-KEYWORD,voddazn␊
    ␊
    # > Disney+␊
    DOMAIN-SUFFIX,bamgrid.com␊
    DOMAIN-SUFFIX,disney-plus.net␊
    DOMAIN-SUFFIX,disneyplus.com␊
    DOMAIN-SUFFIX,dssott.com␊
    DOMAIN,cdn.registerdisney.go.com␊
    ␊
    # > encoreTVB␊
    DOMAIN-SUFFIX,encoretvb.com␊
    DOMAIN,edge.api.brightcove.com␊
    DOMAIN,bcbolt446c5271-a.akamaihd.net␊
    ␊
    # > Fox+ & Fox Now␊
    DOMAIN-SUFFIX,dashasiafox.akamaized.net␊
    DOMAIN-SUFFIX,fox.com␊
    DOMAIN-SUFFIX,foxdcg.com␊
    DOMAIN-SUFFIX,foxplus.com␊
    DOMAIN-SUFFIX,staticasiafox.akamaized.net␊
    DOMAIN-SUFFIX,theplatform.com␊
    DOMAIN-SUFFIX,uplynk.com␊
    ␊
    # > HBO Now & HBO GO␊
    DOMAIN-SUFFIX,hbo.com␊
    DOMAIN-SUFFIX,hbogo.com␊
    DOMAIN-SUFFIX,hboasia.com␊
    DOMAIN-SUFFIX,hbogo.com␊
    DOMAIN-SUFFIX,hbogoasia.hk␊
    DOMAIN,44wilhpljf.execute-api.ap-southeast-1.amazonaws.com␊
    DOMAIN,bcbolthboa-a.akamaihd.net␊
    DOMAIN,cf-images.ap-southeast-1.prod.boltdns.net␊
    DOMAIN,manifest.prod.boltdns.net␊
    DOMAIN,s3-ap-southeast-1.amazonaws.com␊
    # > 华文电视␊
    DOMAIN-SUFFIX,5itv.tv␊
    DOMAIN-SUFFIX,ocnttv.com␊
    # > Hulu␊
    DOMAIN-SUFFIX,hulu.com␊
    DOMAIN-SUFFIX,huluim.com␊
    DOMAIN-SUFFIX,hulustream.com␊
    # > Hulu(フールー)␊
    DOMAIN-SUFFIX,happyon.jp␊
    DOMAIN-SUFFIX,hulu.jp␊
    # > ITV␊
    DOMAIN-SUFFIX,itv.com␊
    DOMAIN-SUFFIX,itvstatic.com␊
    DOMAIN,itvpnpmobile-a.akamaihd.net␊
    # > KKTV␊
    DOMAIN-SUFFIX,kktv.com.tw␊
    DOMAIN-SUFFIX,kktv.me␊
    DOMAIN,kktv-theater.kk.stream␊
    # > Line TV␊
    DOMAIN-SUFFIX,linetv.tw␊
    DOMAIN,d3c7rimkq79yfu.cloudfront.net␊
    # > LiTV␊
    DOMAIN-SUFFIX,litv.tv␊
    DOMAIN,litvfreemobile-hichannel.cdn.hinet.net␊
    # > My5␊
    DOMAIN-SUFFIX,channel5.com␊
    DOMAIN-SUFFIX,my5.tv␊
    DOMAIN,d349g9zuie06uo.cloudfront.net␊
    # > myTV SUPER␊
    DOMAIN-SUFFIX,mytvsuper.com␊
    DOMAIN-SUFFIX,tvb.com␊
    # > Netflix␊
    DOMAIN-SUFFIX,netflix.com␊
    DOMAIN-SUFFIX,netflix.net␊
    DOMAIN-SUFFIX,nflxext.com␊
    DOMAIN-SUFFIX,nflximg.com␊
    DOMAIN-SUFFIX,nflximg.net␊
    DOMAIN-SUFFIX,nflxso.net␊
    DOMAIN-SUFFIX,nflxvideo.net␊
    IP-CIDR,23.246.0.0/18␊
    IP-CIDR,37.77.184.0/21␊
    IP-CIDR,45.57.0.0/17␊
    IP-CIDR,64.120.128.0/17␊
    IP-CIDR,66.197.128.0/17␊
    IP-CIDR,108.175.32.0/20␊
    IP-CIDR,192.173.64.0/18␊
    IP-CIDR,198.38.96.0/19␊
    IP-CIDR,198.45.48.0/20␊
    # > niconico␊
    DOMAIN-SUFFIX,dmc.nico␊
    DOMAIN-SUFFIX,nicovideo.jp␊
    DOMAIN-SUFFIX,nimg.jp␊
    DOMAIN-SUFFIX,socdm.com␊
    # > PBS␊
    DOMAIN-SUFFIX,pbs.org␊
    # > Pornhub␊
    DOMAIN-SUFFIX,phncdn.com␊
    DOMAIN-SUFFIX,pornhub.com␊
    DOMAIN-SUFFIX,pornhubpremium.com␊
    # > 台湾好␊
    DOMAIN-SUFFIX,skyking.com.tw␊
    DOMAIN,hamifans.emome.net␊
    # > Twitch␊
    DOMAIN-SUFFIX,twitch.tv␊
    DOMAIN-SUFFIX,twitchcdn.net␊
    DOMAIN-SUFFIX,ttvnw.net␊
    # > ViuTV␊
    DOMAIN-SUFFIX,viu.com␊
    DOMAIN-SUFFIX,viu.tv␊
    DOMAIN,api.viu.now.com␊
    DOMAIN,d1k2us671qcoau.cloudfront.net␊
    DOMAIN,d2anahhhmp1ffz.cloudfront.net␊
    DOMAIN,dfp6rglgjqszk.cloudfront.net␊
    # > YouTube␊
    DOMAIN-SUFFIX,googlevideo.com␊
    DOMAIN-SUFFIX,youtube.com␊
    DOMAIN,youtubei.googleapis.com␊
    `

## stringify

> Snapshot 1

    `foo: bar␊
    `

> Snapshot 2

    '{"foo":"bar"}'

## loadLocalSnippet

> Snapshot 1

    `USER-AGENT,com.google.ios.youtube*,Proxy␊
    USER-AGENT,YouTube*,Proxy␊
    DOMAIN-SUFFIX,googlevideo.com,Proxy␊
    DOMAIN-SUFFIX,youtube.com,Proxy␊
    DOMAIN,youtubei.googleapis.com,Proxy␊
    PROCESS-NAME,YT Music,Proxy␊
    `
