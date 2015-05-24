# `<z-icon>`

Icons encapsulated from [glyphicons](http://glyphicons.com/)

## Import

```
<link rel="import" href="z-icon/z-icon.html">
```

## Attributes

- `name`: the icon name

## Examples

```
<style>
  p[case="z-icon"] {max-height: 320px; overflow: auto; padding: 10px 15px; border-radius: 5px; border: 1px #ccc solid;}
  p[case="z-icon"] > span {cursor: pointer; color: #999; width: 240px; display: inline-block;}
  p[case="z-icon"] > span:hover {color: #000;}
  p[case="z-icon"] > span:active {color: #F60;}
  p[case="z-icon"] z-icon {font-size: 24px; vertical-align: middle;}
</style>

<p case="z-icon">
  <span><z-icon name="asterisk"></z-icon> asterisk</span>
  <span><z-icon name="plus"></z-icon> plus</span>
  <span><z-icon name="euro"></z-icon> euro</span>
  <span><z-icon name="minus"></z-icon> minus</span>
  <span><z-icon name="cloud"></z-icon> cloud</span>
  <span><z-icon name="envelope"></z-icon> envelope</span>
  <span><z-icon name="pencil"></z-icon> pencil</span>
  <span><z-icon name="glass"></z-icon> glass</span>
  <span><z-icon name="music"></z-icon> music</span>
  <span><z-icon name="search"></z-icon> search</span>
  <span><z-icon name="heart"></z-icon> heart</span>
  <span><z-icon name="star"></z-icon> star</span>
  <span><z-icon name="star-empty"></z-icon> star-empty</span>
  <span><z-icon name="user"></z-icon> user</span>
  <span><z-icon name="film"></z-icon> film</span>
  <span><z-icon name="th-large"></z-icon> th-large</span>
  <span><z-icon name="th"></z-icon> th</span>
  <span><z-icon name="th-list"></z-icon> th-list</span>
  <span><z-icon name="ok"></z-icon> ok</span>
  <span><z-icon name="remove"></z-icon> remove</span>
  <span><z-icon name="zoom-in"></z-icon> zoom-in</span>
  <span><z-icon name="zoom-out"></z-icon> zoom-out</span>
  <span><z-icon name="off"></z-icon> off</span>
  <span><z-icon name="signal"></z-icon> signal</span>
  <span><z-icon name="cog"></z-icon> cog</span>
  <span><z-icon name="trash"></z-icon> trash</span>
  <span><z-icon name="home"></z-icon> home</span>
  <span><z-icon name="file"></z-icon> file</span>
  <span><z-icon name="time"></z-icon> time</span>
  <span><z-icon name="road"></z-icon> road</span>
  <span><z-icon name="download-alt"></z-icon> download-alt</span>
  <span><z-icon name="download"></z-icon> download</span>
  <span><z-icon name="upload"></z-icon> upload</span>
  <span><z-icon name="inbox"></z-icon> inbox</span>
  <span><z-icon name="play-circle"></z-icon> play-circle</span>
  <span><z-icon name="repeat"></z-icon> repeat</span>
  <span><z-icon name="refresh"></z-icon> refresh</span>
  <span><z-icon name="list-alt"></z-icon> list-alt</span>
  <span><z-icon name="lock"></z-icon> lock</span>
  <span><z-icon name="flag"></z-icon> flag</span>
  <span><z-icon name="headphones"></z-icon> headphones</span>
  <span><z-icon name="volume-off"></z-icon> volume-off</span>
  <span><z-icon name="volume-down"></z-icon> volume-down</span>
  <span><z-icon name="volume-up"></z-icon> volume-up</span>
  <span><z-icon name="qrcode"></z-icon> qrcode</span>
  <span><z-icon name="barcode"></z-icon> barcode</span>
  <span><z-icon name="tag"></z-icon> tag</span>
  <span><z-icon name="tags"></z-icon> tags</span>
  <span><z-icon name="book"></z-icon> book</span>
  <span><z-icon name="bookmark"></z-icon> bookmark</span>
  <span><z-icon name="print"></z-icon> print</span>
  <span><z-icon name="camera"></z-icon> camera</span>
  <span><z-icon name="font"></z-icon> font</span>
  <span><z-icon name="bold"></z-icon> bold</span>
  <span><z-icon name="italic"></z-icon> italic</span>
  <span><z-icon name="text-height"></z-icon> text-height</span>
  <span><z-icon name="text-width"></z-icon> text-width</span>
  <span><z-icon name="align-left"></z-icon> align-left</span>
  <span><z-icon name="align-center"></z-icon> align-center</span>
  <span><z-icon name="align-right"></z-icon> align-right</span>
  <span><z-icon name="align-justify"></z-icon> align-justify</span>
  <span><z-icon name="list"></z-icon> list</span>
  <span><z-icon name="indent-left"></z-icon> indent-left</span>
  <span><z-icon name="indent-right"></z-icon> indent-right</span>
  <span><z-icon name="facetime-video"></z-icon> facetime-video</span>
  <span><z-icon name="picture"></z-icon> picture</span>
  <span><z-icon name="map-marker"></z-icon> map-marker</span>
  <span><z-icon name="adjust"></z-icon> adjust</span>
  <span><z-icon name="tint"></z-icon> tint</span>
  <span><z-icon name="edit"></z-icon> edit</span>
  <span><z-icon name="share"></z-icon> share</span>
  <span><z-icon name="check"></z-icon> check</span>
  <span><z-icon name="move"></z-icon> move</span>
  <span><z-icon name="step-backward"></z-icon> step-backward</span>
  <span><z-icon name="fast-backward"></z-icon> fast-backward</span>
  <span><z-icon name="backward"></z-icon> backward</span>
  <span><z-icon name="play"></z-icon> play</span>
  <span><z-icon name="pause"></z-icon> pause</span>
  <span><z-icon name="stop"></z-icon> stop</span>
  <span><z-icon name="forward"></z-icon> forward</span>
  <span><z-icon name="fast-forward"></z-icon> fast-forward</span>
  <span><z-icon name="step-forward"></z-icon> step-forward</span>
  <span><z-icon name="eject"></z-icon> eject</span>
  <span><z-icon name="chevron-left"></z-icon> chevron-left</span>
  <span><z-icon name="chevron-right"></z-icon> chevron-right</span>
  <span><z-icon name="plus-sign"></z-icon> plus-sign</span>
  <span><z-icon name="minus-sign"></z-icon> minus-sign</span>
  <span><z-icon name="remove-sign"></z-icon> remove-sign</span>
  <span><z-icon name="ok-sign"></z-icon> ok-sign</span>
  <span><z-icon name="question-sign"></z-icon> question-sign</span>
  <span><z-icon name="info-sign"></z-icon> info-sign</span>
  <span><z-icon name="screenshot"></z-icon> screenshot</span>
  <span><z-icon name="remove-circle"></z-icon> remove-circle</span>
  <span><z-icon name="ok-circle"></z-icon> ok-circle</span>
  <span><z-icon name="ban-circle"></z-icon> ban-circle</span>
  <span><z-icon name="arrow-left"></z-icon> arrow-left</span>
  <span><z-icon name="arrow-right"></z-icon> arrow-right</span>
  <span><z-icon name="arrow-up"></z-icon> arrow-up</span>
  <span><z-icon name="arrow-down"></z-icon> arrow-down</span>
  <span><z-icon name="share-alt"></z-icon> share-alt</span>
  <span><z-icon name="resize-full"></z-icon> resize-full</span>
  <span><z-icon name="resize-small"></z-icon> resize-small</span>
  <span><z-icon name="exclamation-sign"></z-icon> exclamation-sign</span>
  <span><z-icon name="gift"></z-icon> gift</span>
  <span><z-icon name="leaf"></z-icon> leaf</span>
  <span><z-icon name="fire"></z-icon> fire</span>
  <span><z-icon name="eye-open"></z-icon> eye-open</span>
  <span><z-icon name="eye-close"></z-icon> eye-close</span>
  <span><z-icon name="warning-sign"></z-icon> warning-sign</span>
  <span><z-icon name="plane"></z-icon> plane</span>
  <span><z-icon name="calendar"></z-icon> calendar</span>
  <span><z-icon name="random"></z-icon> random</span>
  <span><z-icon name="comment"></z-icon> comment</span>
  <span><z-icon name="magnet"></z-icon> magnet</span>
  <span><z-icon name="chevron-up"></z-icon> chevron-up</span>
  <span><z-icon name="chevron-down"></z-icon> chevron-down</span>
  <span><z-icon name="retweet"></z-icon> retweet</span>
  <span><z-icon name="shopping-cart"></z-icon> shopping-cart</span>
  <span><z-icon name="folder-close"></z-icon> folder-close</span>
  <span><z-icon name="folder-open"></z-icon> folder-open</span>
  <span><z-icon name="resize-vertical"></z-icon> resize-vertical</span>
  <span><z-icon name="resize-horizontal"></z-icon> resize-horizontal</span>
  <span><z-icon name="hdd"></z-icon> hdd</span>
  <span><z-icon name="bullhorn"></z-icon> bullhorn</span>
  <span><z-icon name="bell"></z-icon> bell</span>
  <span><z-icon name="certificate"></z-icon> certificate</span>
  <span><z-icon name="thumbs-up"></z-icon> thumbs-up</span>
  <span><z-icon name="thumbs-down"></z-icon> thumbs-down</span>
  <span><z-icon name="hand-right"></z-icon> hand-right</span>
  <span><z-icon name="hand-left"></z-icon> hand-left</span>
  <span><z-icon name="hand-up"></z-icon> hand-up</span>
  <span><z-icon name="hand-down"></z-icon> hand-down</span>
  <span><z-icon name="circle-arrow-right"></z-icon> circle-arrow-right</span>
  <span><z-icon name="circle-arrow-left"></z-icon> circle-arrow-left</span>
  <span><z-icon name="circle-arrow-up"></z-icon> circle-arrow-up</span>
  <span><z-icon name="circle-arrow-down"></z-icon> circle-arrow-down</span>
  <span><z-icon name="globe"></z-icon> globe</span>
  <span><z-icon name="wrench"></z-icon> wrench</span>
  <span><z-icon name="tasks"></z-icon> tasks</span>
  <span><z-icon name="filter"></z-icon> filter</span>
  <span><z-icon name="briefcase"></z-icon> briefcase</span>
  <span><z-icon name="fullscreen"></z-icon> fullscreen</span>
  <span><z-icon name="dashboard"></z-icon> dashboard</span>
  <span><z-icon name="paperclip"></z-icon> paperclip</span>
  <span><z-icon name="heart-empty"></z-icon> heart-empty</span>
  <span><z-icon name="link"></z-icon> link</span>
  <span><z-icon name="phone"></z-icon> phone</span>
  <span><z-icon name="pushpin"></z-icon> pushpin</span>
  <span><z-icon name="usd"></z-icon> usd</span>
  <span><z-icon name="gbp"></z-icon> gbp</span>
  <span><z-icon name="sort"></z-icon> sort</span>
  <span><z-icon name="sort-by-alphabet"></z-icon> sort-by-alphabet</span>
  <span><z-icon name="sort-by-alphabet-alt"></z-icon> sort-by-alphabet-alt</span>
  <span><z-icon name="sort-by-order"></z-icon> sort-by-order</span>
  <span><z-icon name="sort-by-order-alt"></z-icon> sort-by-order-alt</span>
  <span><z-icon name="sort-by-attributes"></z-icon> sort-by-attributes</span>
  <span><z-icon name="sort-by-attributes-alt"></z-icon> sort-by-attributes-alt</span>
  <span><z-icon name="unchecked"></z-icon> unchecked</span>
  <span><z-icon name="expand"></z-icon> expand</span>
  <span><z-icon name="collapse-down"></z-icon> collapse-down</span>
  <span><z-icon name="collapse-up"></z-icon> collapse-up</span>
  <span><z-icon name="log-in"></z-icon> log-in</span>
  <span><z-icon name="flash"></z-icon> flash</span>
  <span><z-icon name="log-out"></z-icon> log-out</span>
  <span><z-icon name="new-window"></z-icon> new-window</span>
  <span><z-icon name="record"></z-icon> record</span>
  <span><z-icon name="save"></z-icon> save</span>
  <span><z-icon name="open"></z-icon> open</span>
  <span><z-icon name="saved"></z-icon> saved</span>
  <span><z-icon name="import"></z-icon> import</span>
  <span><z-icon name="export"></z-icon> export</span>
  <span><z-icon name="send"></z-icon> send</span>
  <span><z-icon name="floppy-disk"></z-icon> floppy-disk</span>
  <span><z-icon name="floppy-saved"></z-icon> floppy-saved</span>
  <span><z-icon name="floppy-remove"></z-icon> floppy-remove</span>
  <span><z-icon name="floppy-save"></z-icon> floppy-save</span>
  <span><z-icon name="floppy-open"></z-icon> floppy-open</span>
  <span><z-icon name="credit-card"></z-icon> credit-card</span>
  <span><z-icon name="transfer"></z-icon> transfer</span>
  <span><z-icon name="cutlery"></z-icon> cutlery</span>
  <span><z-icon name="header"></z-icon> header</span>
  <span><z-icon name="compressed"></z-icon> compressed</span>
  <span><z-icon name="earphone"></z-icon> earphone</span>
  <span><z-icon name="phone-alt"></z-icon> phone-alt</span>
  <span><z-icon name="tower"></z-icon> tower</span>
  <span><z-icon name="stats"></z-icon> stats</span>
  <span><z-icon name="sd-video"></z-icon> sd-video</span>
  <span><z-icon name="hd-video"></z-icon> hd-video</span>
  <span><z-icon name="subtitles"></z-icon> subtitles</span>
  <span><z-icon name="sound-stereo"></z-icon> sound-stereo</span>
  <span><z-icon name="sound-dolby"></z-icon> sound-dolby</span>
  <span><z-icon name="sound-5-1"></z-icon> sound-5-1</span>
  <span><z-icon name="sound-6-1"></z-icon> sound-6-1</span>
  <span><z-icon name="sound-7-1"></z-icon> sound-7-1</span>
  <span><z-icon name="copyright-mark"></z-icon> copyright-mark</span>
  <span><z-icon name="registration-mark"></z-icon> registration-mark</span>
  <span><z-icon name="cloud-download"></z-icon> cloud-download</span>
  <span><z-icon name="cloud-upload"></z-icon> cloud-upload</span>
  <span><z-icon name="tree-conifer"></z-icon> tree-conifer</span>
  <span><z-icon name="tree-deciduous"></z-icon> tree-deciduous</span>
</p>
```
