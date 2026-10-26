# Training Planner Privacy

The public website for the Training Planner app: the **privacy policy** (`index.html`) and the
**support page** (`support.html`), hosted free with GitHub Pages from the
[training-planner-privacy](https://github.com/drew0ps/training-planner-privacy) repository.

- Privacy policy: <https://drew0ps.github.io/training-planner-privacy/>
- Support: <https://drew0ps.github.io/training-planner-privacy/support.html>

Both URLs are entered in App Store Connect (App Information › Privacy Policy URL; the support URL).
App Review needs them, the more so because the app uses HealthKit.

## Editing

Plain static HTML, no build step: edit a page, push to `main`, and Pages republishes within a
minute or so. The privacy policy text must stay in sync with the in-app copy at
`Training Planner/Training Planner/Resources/PrivacyPolicy.md` - change both together, with a new
"Effective" date when the meaning changes.
