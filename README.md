# hexo-tag-embed

[![Tester](https://github.com/hexojs/hexo-tag-embed/actions/workflows/tester.yml/badge.svg)](https://github.com/hexojs/hexo-tag-embed/actions/workflows/tester.yml)

# Usage

## Gist

To embed a Gist snippet:

```ejs
{% gist gist_id [filename] %}
```

## jsFiddle

To embed a jsFiddle snippet:

```ejs
{% jsfiddle shorttag [tabs] [skin] [width] [height] %}
```

## Vimeo

Inserts a responsive or specified size Vimeo video.

```ejs
{% vimeo video_id [width] [height] %}
```

## YouTube

Inserts a YouTube video.

```ejs
{% youtube video_id [type] [cookie] %}
```

### Examples

Embed a video

```ejs
{% youtube lJIrF4YjHfQ %}
```

Embed a playlist

```ejs
{% youtube PL9hW1uS6HUfscJ9DHkOSoOX45MjXduUxo 'playlist' %}
```

Enable privacy-enhanced mode

YouTube’s cookie is not used in this mode.

```ejs
{% youtube lJIrF4YjHfQ false %}
{% youtube PL9hW1uS6HUfscJ9DHkOSoOX45MjXduUxo 'playlist' false %}
```

## LICENSE

MIT