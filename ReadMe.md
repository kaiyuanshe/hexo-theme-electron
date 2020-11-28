# hexo-theme-electron

a [Hexo theme][1] forked from [Electron.js official Web-site][2], built for kinds of NGOs.

[![NPM Dependency](https://david-dm.org/kaiyuanshe/hexo-theme-electron.svg)][3]

## Demo

https://kaiyuanshe.cn/

## Usage

```Shell
npm init hexo-wiki create repo_name \
    --theme electron \
    --remote https://github.com/your_id/repo_name.git
cd repo_name
npm install icalendar
```

## Features

### Components

1. [File list](layout/component/files.ejs)
2. [Member list](layout/component/members.ejs)
3. [Team roster](layout/component/team.ejs)
4. [Activity calendar](layout/component/calendar.ejs)
    - https://fullcalendar.io/docs/v3
5. [Marker map](layout/component/marker_map.ejs)
    - https://lbs.amap.com/api/javascript-api/summary
6. [Activity summary](layout/component/activity.ejs)

### Layouts

### Helpers

1. [hasCategory()](scripts/index.js#L30)
2. [fileType()](scripts/index.js#L43)
3. [toDataURI()](scripts/index.js#L53)
4. [eventOf()](scripts/index.js#L59)

[1]: https://hexo.io/docs/themes
[2]: https://github.com/electron/electronjs.org
[3]: https://david-dm.org/kaiyuanshe/hexo-theme-electron
