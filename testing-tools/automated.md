# CLIs

## Pa11y (CLI)

### Install

```
npm install -g pa11y-ci
```

### Use

```
pa11y [options] <url>
```

## Axe (CLI)

### Install

```
npm install -g axe-cli
```

### Use

```
axe <url>
```

# Browser extensions

## Chrome Accessibility Developer Tools

### Install

[Add to Chrome here](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)

### Use

Open the **Audits** tab in developer tools and perform an audit of the current page.

## Lighthouse

### Install

[Add to Chrome here](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)

### Use

Open the **Audits** tab in developer tools and perform an audit of the current page.

## aXe

### Install

[Add to Chrome here](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)

### Use

Perform audits from developer tools' dedicated **aXe** tab.

# Bookmarklets

## HTML Code Sniffer

This tool works as a bookmarklet and has a high degree of accuracy. Drag the [bookmarklet](http://squizlabs.github.io/HTML_CodeSniffer/) to your bookmarks bar and click the bookmarklet on the component page you want to test. Make sure "Standards" is set to WCAG2AA from the dropdown. Ignore notices, but test warnings manually if you believe there may be a real issue.
