# OBS-web (Static Build)

[![All Contributors](https://img.shields.io/badge/all_contributors-18-orange.svg?style=flat-square)](#contributors-)
#### The easiest way to control [OBS](https://obsproject.com/) remotely. This is a pre-compiled, static version of OBS-web.

### **Live URL: https://rad-nerd.github.io/obs-web-static/**

---

#### Screenshot:

![Screenshot of OBS-web](.github/screenshot.png)

#### Features:

- **Zero Installation:** No node_modules or build steps required. Just host these files and it works.
- **Universal Access:** Works in any modern browser (desktop + mobile).
- **Control:** Support for local network and internet control through [WSS tunnels](https://github.com/obsproject/obs-websocket/blob/4.x-compat/SSL-TUNNELLING.md).
- **Functionality:** Easily switch scenes, start/stop streaming, recording, and Virtual Camera.
- **Studio Mode:** Full support for preview and program scenes.
- **Live Feed:** View of preview & output, updating at 1 fps.
- **Extras:** Wakelock support (keeps screen on), profile/collection switching, and hidden scene support.

---

#### Requirements:

- [OBS](https://obsproject.com/) v28 or higher (includes built-in obs-websocket).
- Enabling the server in OBS under `Tools -> obs-websocket Settings -> Enable WebSocket Server`.

---

#### Static Deployment:

This repository contains the **compiled production build**. You do not need `npm` or `vite` to run this. To host your own version:
1. Fork this repo.
2. Enable **GitHub Pages** in settings.
3. Point it to the `master` branch.

---

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/verstaerker-583"><img src="https://avatars2.githubusercontent.com/u/40574338?v=4?s=100" width="100px;" alt="verstaerker-583"/><br /><sub><b>verstaerker-583</b></sub></a><br /><a href="https://github.com/Niek/obs-web/commits?author=verstaerker-583" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://crazy4groovy.blogspot.ca"><img src="https://avatars0.githubusercontent.com/u/1110812?v=4?s=100" width="100px;" alt="crazy4groovy"/><br /><sub><b>crazy4groovy</b></sub></a><br /><a href="https://github.com/Niek/obs-web/issues?q=author%3Acrazy4groovy" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/isctylr"><img src="https://avatars0.githubusercontent.com/u/24595776?v=4?s=100" width="100px;" alt="Isaac Taylor"/><br /><sub><b>Isaac Taylor</b></sub></a><br /><a href="https://github.com/Niek/obs-web/commits?author=isctylr" title="Code">💻</a> <a href="#ideas-isctylr" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/darthclide"><img src="https://avatars1.githubusercontent.com/u/46735828?v=4?s=100" width="100px;" alt="darthclide"/><br /><sub><b>darthclide</b></sub></a><br /><a href="https://github.com/Niek/obs-web/issues?q=author%3Adarthclide" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://blog.rodrigograca.com/"><img src="https://avatars2.githubusercontent.com/u/1134310?v=4?s=100" width="100px;" alt="Rodrigo Graça"/><br /><sub><b>Rodrigo Graça</b></sub></a><br /><a href="https://github.com/Niek/obs-web/commits?author=rodrigograca31" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/feitosa-daniel"><img src="https://avatars2.githubusercontent.com/u/1847734?v=4?s=100" width="100px;" alt="Daniel Feitosa"/><br /><sub><b>Daniel Feitosa</b></sub></a><br /><a href="https://github.com/Niek/obs-web/commits?author=feitosa-daniel" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://linkedin.com/in/arun-woosaree"><img src="https://avatars1.githubusercontent.com/u/8227297?v=4?s=100" width="100px;" alt="Arun Woosaree"/><br /><sub><b>Arun Woosaree</b></sub></a><br /><a href="https://github.com/Niek/obs-web/commits?author=Arunscape" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>
