mkv25.net monitor
=================

What it looks like
------------------

A product monitor for checking that the mkv25.net site is working properly.

![mkv25.net monitor - what it looks like](images/mkv25-dashboard-what-it-looks-like.png)

Setting up
----------

To setup from scratch, run:
```sh
git clone git@github.com/Markavian/mkv25-monitor.git
cd mkv25-monitor
npm install
node server.js
```

Expected output:
```
[Startup Check] User content directory seems to exist: monitoring

[Startup Check] Content directory seems to exist: monitoring/content

[Startup Check] API directory seems to exist: monitoring/api

[All Checks Complete]

mkv25.net monitor Server started on http://localhost:2500
```

Library Credits
---------------
* [Product Monitor](https://github.com/johnbeech/product-monitor) - mkv25.net monitor is just a thin layer of configuration on top of `product-monitor`, see there for a full list of libraries used.
