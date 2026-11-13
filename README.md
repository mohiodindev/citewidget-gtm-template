# CiteWidget tag template for Google Tag Manager

Adds the [CiteWidget](https://citewidget.com) chat to a website. It answers visitors' questions
from the site owner's own documents and cites the page it used.

The template sets `window.CiteWidgetConfig` and loads
`https://api.citewidget.com/widget/v1/citewidget.js` once per page. It needs a CiteWidget
workspace and its public key (starts with `pk_`; never use a secret key).

## Use

1. Add the template from the Community Template Gallery (Templates > Search Gallery > CiteWidget).
2. Create a tag of this type and enter your public workspace key.
3. Leave the display fields empty to keep the settings from your CiteWidget dashboard.
4. Trigger: Initialization - All Pages (or Page View). Preview, then publish the container.

## Notes

- Only fields you fill in are sent, so dashboard edits keep applying.
- A Content Security Policy nonce cannot be set from a GTM template.
- Permissions requested: inject the one script URL above and write `window.CiteWidgetConfig`.

## Support

Issues and questions: use this repository's Issues, or https://citewidget.com/contact.

## License

Apache License 2.0 (required by the Community Template Gallery). See `LICENSE`.
