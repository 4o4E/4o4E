<!--suppress HtmlDeprecatedAttribute -->

<details>
  <summary><h3>About Me</h3></summary>

```kotlin
object Me {
    val lang = listOf(
        "kotlin",
        "java",
        "ts",
        "js",
        "python",
    )

    val hobby = listOf(
      "bilibili",
      "steam",
      "羽毛球",
      "游泳",
    )

    suspend fun next() = when {
        now().isWorkTime -> ((1..9).map { "工作" } + "摸鱼").random()
        now().isTimeToSleep -> "sleep"
        else -> hobby.random()
    }

    suspend fun life() {
        while (true) {
            withContext(Dispatchers.Main) {
                invoke(next())
            }
        }
    }
}
```
</details>

喜欢[kotlin](https://kotlinlang.org/)的全栈开发者, 但是工作只能用java,
熟悉前端技术栈(`js`/`ts`/`vue`/`react`), 但是主要写后端(`spring`全家桶),
别的技术栈诸如`python`会用但用的不多


<details>
  <summary><h3>最近在写什么</h3></summary>
  使用<code>kotlin</code>喵, 使用<code>kotlin</code>谢谢喵

  好用爱用多用😋
</details>

[![wakatime](https://github-readme-stats-4o4e.vercel.app/api/wakatime?username=404E&range=last_30_days&layout=compact&theme=radical)](https://wakatime.com/@404E)

### 以前做的mc项目

<details>
  <summary><h4>Bukkit 插件</h4></summary>

- [**Boom**](https://github.com/4o4E/Boom/)

  [![Mcbbs](https://raw.githubusercontent.com/4o4E/4o4E/main/mcbbs.svg)](https://www.mcbbs.net/thread-1150139-1-1.html)
  [![Stars](https://img.shields.io/github/stars/4o4E/Boom)](https://github.com/4o4E/Boom/stargazers)
  [![Downloads](https://img.shields.io/github/downloads/4o4E/Boom/total)](https://github.com/4o4E/Boom/releases/latest)
  [![Release](https://img.shields.io/github/v/release/4o4E/Boom)](https://github.com/4o4E/Boom/releases)
  <div>
  <a href="https://bstats.org/plugin/bukkit/Boom">
  <img style="width: 60%;" src="https://bstats.org/signatures/bukkit/Boom.svg" alt="Bstats"/>
  </a>
  </div>

- [**EClean**](https://github.com/4o4E/EClean/)

  [![Mcbbs](https://raw.githubusercontent.com/4o4E/4o4E/main/mcbbs.svg)](https://www.mcbbs.net/thread-1305548-1-1.html)
  [![Stars](https://img.shields.io/github/stars/4o4E/EClean)](https://github.com/4o4E/EClean/stargazers)
  [![Downloads](https://img.shields.io/github/downloads/4o4E/EClean/total)](https://github.com/4o4E/EClean/releases/latest)
  [![Release](https://img.shields.io/github/v/release/4o4E/EClean)](https://github.com/4o4E/EClean/releases)
  <div>
  <a href="https://bstats.org/plugin/bukkit/EClean">
  <img style="width: 60%;" src="https://bstats.org/signatures/bukkit/EClean.svg" alt="Bstats"/>
  </a>
  </div>
</details>

<details>
  <summary><h4>Minecraft 材质</h4></summary>

- [**DynamicGlowOre**](https://github.com/4o4E/DynamicGlowOre/)

  [![Mcbbs](https://raw.githubusercontent.com/4o4E/4o4E/main/mcbbs.svg)](https://www.mcbbs.net/thread-1204050-1-1.html)
  [![Stars](https://img.shields.io/github/stars/4o4E/DynamicGlowOre)](https://github.com/4o4E/DynamicGlowOre/stargazers)
  [![Downloads](https://img.shields.io/github/downloads/4o4E/DynamicGlowOre/total)](https://github.com/4o4E/DynamicGlowOre/releases/latest)
  [![Release](https://img.shields.io/github/v/release/4o4E/DynamicGlowOre)](https://github.com/4o4E/DynamicGlowOre/releases)

- [**DarkMode**](https://github.com/4o4E/DarkMode/)

  [![Mcbbs](https://raw.githubusercontent.com/4o4E/4o4E/main/mcbbs.svg)](https://www.mcbbs.net/thread-1365041-1-1.html)
  [![Stars](https://img.shields.io/github/stars/4o4E/DarkMode)](https://github.com/4o4E/DarkMode/stargazers)
  [![Downloads](https://img.shields.io/github/downloads/4o4E/DarkMode/total)](https://github.com/4o4E/DarkMode/releases/latest)
  [![Release](https://img.shields.io/github/v/release/4o4E/DarkMode)](https://github.com/4o4E/DarkMode/releases)

</details>

