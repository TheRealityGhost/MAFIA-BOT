
# 𝚃𝙷𝙴 𝙼𝙰𝙵𝙸𝙰𝙱𝙾𝚃
This is a userbot made for telegram. I made this userbot with help of all other userbots available in telegram. All credits goes to its Respective Owners....

[![MAFIABOT LOGO](https://te.legra.ph/file/a95cc01983cbdc198b5a3.jpg)](https://t.me/TheRealityGhost)


# FORK AT YOUR OWN RISK

<details>

  <summary> • INSTALLING • </summary>

### The Easy Way

<h4>⚜️ DEPLOY TO HEROKU ⚜️</h4>

<a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FTheRealityGhost%2FMafiaBot&template=https%3A%2F%2Fgithub.com%2FMafiaBotOP%2FMafiaBot" rel="nofollow" style="background-color: initial; box-sizing: border-box; color: #0366d6; text-decoration-line: none;"><img alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.svg" src="https://camo.githubusercontent.com/83b0e95b38892b49184e07ad572c94c8038323fb/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667" style="border-style: none; box-sizing: initial; max-width: 100%;" /></a></div>

</details>

<details>

  <summary> • THE NORMAL WAY • </summary>

Simply clone the repository and run the main file:
```sh
git clone https://github.com/TheRealityGhost/MAFIA-BOT.git
cd MAFIA-BOT
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

</details>

<details>

  <summary> • UNIBORG CONFIGURATION • </summary>

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Fortunately there are no Mandatory vars for the UniBorg Support Config.

</details>

<details>

  <summary> • MANDATORY VARS • </summary>

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

</details>

<details>

  <summary> • LICENSE • </summary>

![](https://www.gnu.org/graphics/gplv3-or-later.png)

Copyright (C) 2021

it under the terms of the GNU General Public License as published by

the Free Software Foundation, either version 3 of the License, or

(at your option) any later version.

This program is distributed in the hope that it will be useful,

but WITHOUT ANY WARRANTY; without even the implied warranty of

MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the

GNU General Public License for more details.

You should have received a copy of the GNU General Public License

along with this program. If not, see <https://www.gnu.org/licenses/>.

</details>
