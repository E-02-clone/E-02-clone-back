# E-02-clone-back

# ๐๏ธ์์ด๋น์ค๋น ํด๋ก ์ฝ๋ฉ โ๏ธ

# ๐ Web Site

https://e-02-clfe.vercel.app/

<br>

---

# ๐ฌ ์์ฐ์์

https://youtu.be/x857WQ6KLes

<br>

---

# ๐ ํ์

๐ BACK-END

- ๊น๋์ : sign / login, ๋น๋ฐ๋ฒํธ ์ํธํ
- ์์ง์ฝ : ๊ฒ์๊ธ CRUD, ์ฐํ๊ธฐ, ์ฐ๋ชฉ๋ก, ๋ฌดํ์คํฌ๋กค, ๊ฒ์
- ์ ์น๊ท : ๋๊ธ CRUD, swagger

<br>
๐ FRONT-END

- ๋ฐ์ขํ : ํ์๊ฐ์, ๋ก๊ทธ์ธ, ๋ฉ์ธํ์ด์ง :์นดํ๊ณ ๋ฆฌ, ์ข์์
- ๋ฌธ๋ํ : ์์ธํ์ด์ง , ๊ธ์์ฑ ํ์ด์ง, ๊ธ ์์ , ์ญ์ , s3
- ๊น์ค์ฒ  : ํ๊ธฐ CRUD, ๋ณ์ 

ํ๋ก ํธ : https://github.com/E-02-clone/E-02-clone-front

<br>

---

# ๊ธฐ๋ฅ ๊ตฌํ

๐ ํ์๊ฐ์ ๋ฐ ๋ก๊ทธ์ธ ๊ธฐ๋ฅ ์ฌ์ฉ(์์๋ก๊ทธ์ธ ๋ฏธ์ฌ์ฉ)

๐ ํธ์คํ ๊ธฐ๋ฅ(์ฃผ์์ฐพ๊ธฐ ๋ฏธ์ฌ์ฉ)

๐ ์์ ์ฐํ๊ธฐ / ์ฐํ ์์ ๋ชจ์๋ณด๊ธฐ

๐ ์นดํ๊ณ ๋ฆฌ๋ณ ์์ ๋ณด์ฌ์ฃผ๊ธฐ

๐ ์ ๋ชฉ ๋ฐ ์์น ๊ธฐ๋ฐ ํค์๋ ๊ฒ์

๐ ๋น๋ฐ๋ฒํธ ์ํธํ, swagger๋ฅผ ์ด์ฉํ api๋ช์ธ ์์ฑ

๐ letsencrypt์ ์ฌ์ฉํด์ https ์ค์ 

<br>

---

# ๐  tools

<!-- <img src="https://img.shields.io/badge/์ด๋ฆ-์์์ฝ๋?style=flat-square&logo=๋ก๊ณ ๋ช&logoColor=๋ก๊ณ ์"/> -->

๐ BackEnd

<img src="https://img.shields.io/badge/javascript-333333?style=flat-square&logo=javascript&logoColor=yellow"/> <img src="https://img.shields.io/badge/mysql-3333ff?style=flat-square&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/express-666666?style=flat-square&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-33cc00?style=flat-square&logo=Node.js&logoColor=white"/>

<img src="https://img.shields.io/badge/NPM-33cc00?style=flat-square&logo=NPM.js&logoColor=red"/> <img src="https://img.shields.io/badge/JSON WEB TOKEN-333333?style=flat-square&logo=json web token&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-ffcc33?style=flat-square&logo=AWS&logoColor=white"/>
<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/>

<img src="https://img.shields.io/badge/sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=black"/><img src="https://img.shields.io/badge/swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/><img src="https://img.shields.io/badge/Let's Encrypt-003A70?style=flat-square&logo=Let's Encrypt&logoColor=black"/>

<br>

---

# API ๋ช์ธ์

https://pepper-balmoral-e2e.notion.site/a8fef7e7eef74c65a1f5688870ad9fdb?v=d28a6f5529014bb9803e30dfaf374a5d

---

# ERD ๋ฐ ํ์ด๋ธ ์ค๊ณ

![ERD 1](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/68679b9d-0f9e-488a-ab41-60df601ef788/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220825%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220825T070021Z&X-Amz-Expires=86400&X-Amz-Signature=c7d216c06f3d168441bdb465f4a9bf60702e9e76765f55576c41c29daba40caf&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

---

# ๐BE ์ฐ๋ฆฌ๊ฐ ์๋กญ๊ฒ ๋์ ํ ๊ธฐ์ ๋ค

1. ๋ง์ง๋ง itemkey ๊ฐ์ ์ฌ์ฉํ์ฌ ๋ฌดํ์คํฌ๋กค ๊ธฐ๋ฅ

2. sequelize Op.like %๋ฅผ ์ฌ์ฉํ์ฌ ํค์๋ ๊ฒ์ ๊ธฐ๋ฅ

3. swagger๋ฅผ ์ฌ์ฉํ์ฌ api๋ช์ธ ์์ฑ

4. bcryt๋ฅผ ์ฌ์ฉํ์ฌ ๋น๋ฐ๋ฒํธ ์ํธํ

---

# ๐ค Trouble Shooting

1. ๊ฒ์ ๊ธฐ๋ฅ ๊ตฌํ ์ ํค์๋ ๋จ๋์ผ๋ก ๊ฐ์ด ์กด์ฌํด์ผ๋ง ๊ฒ์์ด ๊ฐ๋ฅํจ '์ค์๋ทฐ' ๊ฒ์์ '์ค์๋ทฐ๋ง์ง'์ ๊ฒ์์ด ์๋จ
   => Op.like๋ฅผ ์ฌ์ฉํ์ฌ %์ค์๋ทฐ%๋ฅผ ํตํ ๊ฒ์์ ์ค์๋ทฐ ์๋ค๋ก ๋ค๋ฅธ ๋ฌธ์์ด์ด ํจ๊ป ์์ด๋ ๊ฒ์์ด ๊ฐ๋ฅํ๊ฒ ํจ

2. ๋ฌดํ์คํฌ๋กค ์คํ์ ๊ธฐ๋ฅ์ ์ค๋ณต, ๋๋ฝ๋๋ ๋ฐ์ดํฐ ๋ฐ์
   => ์ปค์๊ธฐ๋ฐ ํ์ด์ง๋ค์ด์์ ํตํด ๋ง์ง๋ง itemkey ๊ฐ์ ๋ฐ์ ํด๋น key๊ฐ ๋ณด๋ค ์์ ๋ฐ์ดํฐ๋ค์ ๋ณด๋ด์ฃผ์ด ์ค๋ณต, ๋๋ฝ ์๋ ๋ฐ์ดํฐ ์ ์ก์ด ๊ฐ๋ฅํจ
