  <div class="image-container">
    <a href="https://github.com/pripramot/i-studio">
      <p><img loading="lazy" src="https://cdn.hashnode.com/res/hashnode/image/upload/v1709320098585/ad7c1903-a3fb-4d9b-8408-dcba8d278bbf.png?auto=compress,format&amp;format=webp" alt="" class="image--center mx-auto"></p>
    </a>
  </div>

<div align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Github-Pripramot-blue?logo=ankermake&logoColor=blue" alt="mu_ - Pripramot badge">
  </a>
  <a href="https://github.com/ai-jiraphinya">
    <img src="https://img.shields.io/badge/Mint_-Jiraphinya-blue?link=https%3A%2F%2Fgithub.com%2Fai-jiraphinya" alt="Mint_ - Jiraphinya badge">
  </a>
  <a href="https://github.com/pripramot/pripramot/watchers">
    <img src="https://img.shields.io/github/watchers/pripramot/pripramot" alt="GitHub watchers badge">
  </a>
</div>

## โครงสร้าง JSON ง่ายๆ ที่สร้างขึ้นตามตัวอย่าง XML ที่แสดงถึงร้านหนังสือ

```json
{ "store": {
    "book": [ 
      { "category": "reference",
        "author": "Nigel Rees",
        "title": "Sayings of the Century",
        "price": 8.95
      },
      { "category": "fiction",
        "author": "Evelyn Waugh",
        "title": "Sword of Honour",
        "price": 12.99
      },
      { "category": "fiction",
        "author": "Herman Melville",
        "title": "Moby Dick",
        "isbn": "0-553-21311-3",
        "price": 8.99
      },
      { "category": "fiction",
        "author": "J. R. R. Tolkien",
        "title": "The Lord of the Rings",
        "isbn": "0-395-19395-8",
        "price": 22.99
      }
    ],
    "bicycle": {
      "color": "red",
      "price": 19.95
    }
  }
}

```

**short form**

| XPath | JSONPath | Result |
|---|---|---|
| /store/book/author | $.store.book[*].author| the authors of all books in the store |
| //author	| $..author	| all authors |
| /store/* | 	$.store.* | 	all things in store, which are some books and a red bicycle. |
| /store//price | 	$.store..price | 	the price of everything in the store. |
| //book[3] | $..book[2] |	the third book |
| //book[last()] | .. | .. |

<h2 align="center">On the other hand</h2>

<div align="center">
<table>
  <tbody>
    <tr>
      <td align="center" valign="middle" width="600">
        <a href="#" target="_blank">
          <img src="./assets/images/Phra_aphai_mani.jpg">
        </a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<h2 align="center">Create a simple food menu</h2>

### Create a simple food menu
Hide something before placing the desired menu.⏬🦋Press to view
<details>
<summary>Phra Aphai Mani 🦋</summary>
<div align="center">
<table>
  <tbody>
    <tr>
      <td align="center" valign="middle" width="600">
        <a href="https://github.com/My-HackathonEducation-Th/mint" target="_blank">
          <img src="./assets/images/Phra_aphai_mani.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>
</div>
</details>

<div align="center">
<table>
  <tbody>
    <tr>
      <td align="center" valign="middle" width="200">
        <a href="https://acceleanation.com/" target="_blank">
          <img src="./assets/images/500px/30.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/alexksso" target="_blank">
          <img src="./assets/images/500px/26.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/broxen" target="_blank">
          <img src="./assets/images/500px/21.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/xDacon" target="_blank">
          <img src="./assets/images/500px/20.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/GigabiteLabs" target="_blank">
          <img src="./assets/images/500px/10.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://www.hostwiki.com/" target="_blank">
          <img src="./assets/images/500px/15.png">
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/JayDaley" target="_blank">
          <img src="./assets/images/500px/28.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://github.com/idokka" target="_blank">
          <img src="./assets/images/500px/27.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://www.openhost-network.com/" target="_blank">
          <img src="./assets/images/500px/21.png">
        </a>
      </td>
      <td align="center" valign="middle" width="200">
        <a href="https://www.prevo.ch/" target="_blank">
          <img src="./assets/images/500px/22.png">
        </a>
      </td>
      <td align="center" valign="middle" colspan="200">
        <a href="https://github.com/sponsors/NGPixel" target="_blank">
          <img src="./assets/images/500px/25.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>





</td></tr></tbody></table>
</div>
</details>
<h2 align="center">OpenCollective Sponsors</h2>

<h2 align="center">Special Thanks</h2>

![Cloudflare](https://js.wiki/legacy/logo_cloudflare.png)  
[Cloudflare](https://www.cloudflare.com/) for providing their great CDN, SSL and advanced networking services.

![Localazy](https://static.requarks.io/logo/localazy-h40.png)  
[Localazy](https://localazy.com/) for providing access to their great localization service.

![MacStadium](https://static.requarks.io/logo/macstadium-h40.png)  
[MacStadium](https://www.macstadium.com) for providing access to their Mac hardware in the cloud.

![Netlify](https://js.wiki/legacy/logo_netlify.png)  
[Netlify](https://www.netlify.com) for providing hosting for our website.

![ngrok](https://static.requarks.io/logo/ngrok-h40.png)  
[ngrok](https://ngrok.com) for providing access to their great HTTP tunneling services.

---
เทมเพลตโอเพ่นซอร์ส ฟรี สำหรับสร้างเว็บไซต์ของคุณโดยใช้ Astro 4.0+Tailwind CSS. พร้อมสำหรับการเริ่มโครงการใหม่และออกแบบ เรียบง่าย ยึดถือแนวทางปฏิบัติที่ดีที่สุด.! 
