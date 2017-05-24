# learning-center-source
Here you can find all the files __needed to build__ the site "WETHOD Learning Center". 
## Details
* The site is statically generated using [Hugo](https://gohugo.io/);
* The site is hosted on [GitHub Pages](https://pages.github.com/) with a custom domain at http://support.wethod.com;
* If you need a visual editor and/or a simple CMS, you can use [Forestry.io](https://forestry.io);
* The served files are in [another repo](https://github.com/wethod/wethod.github.io). We need to mantain different repositories for source code and served files because of how Forestry.io works;
* The __FAQ__ section embed the [Responsa](https://goresponsa.com/) In-Page widget;
* The __search__ functionality is obtained by using [Algolia DocSearch](https://community.algolia.com/docsearch/).
## How to edit 
Using Forestry.io:
1. Login with the WETHOD account;
2. In the section "My Sites" choose "wethod-learning-center";
3. Edit content;
4. Refresh the github.io page (clearing cache using `⌘ + MAIUSC + R`) to see the changes.

Manually:
1. Clone this repository;
2. Edit content;
3. Push the changes;
4. Forestry.io will detect new commits to this repository and will auto-deploy the site;
5. Refresh the github.io page to see the changes.

## Good to know
In `layout/shortcodes/` you can find useful [shortcodes](https://gohugo.io/extras/shortcodes/) that enhance Markdown's capabilities. 
For example, the __img-center__ shortcode gives you the ability to insert a centered imaged directly from your Markdown:
```
{{< img-center src="/uploads/2017/05/22/add-widget.gif" >}}
```
