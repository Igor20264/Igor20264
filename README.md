<div align="center">

<img src="assets/banner.svg" alt="Igor — Python developer, RTU MIREA, Moscow" width="100%">

Python first. C, C#, and Lua when the runtime needs a closer look.

</div>

## About

I am a Python developer and a student at RTU MIREA in Moscow. Python is home base. C, C#, and Lua are how I get closer to a runtime, a host, or a small tool that should stay out of the way.

Right now that means language modules for [NodeMP](https://github.com/Igor20264/NodeMP-C_ABI-Python). Each one is a C ABI host: CPython, MicroPython, or LuaJIT. Scripts talk to the server through a global `node`, and long work can leave the game tick and run on a thread pinned to one core.

On the backend I built a small booking service: FastAPI, EdgeDB, and Docker, with users and time-slot reservations.

## Stack

<div align="center">

**Languages**

<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img alt="C" src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white">
<img alt="Lua" src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white">
<img alt="LuaJIT" src="https://img.shields.io/badge/LuaJIT-000080?style=for-the-badge&logo=lua&logoColor=white">
<img alt="MicroPython" src="https://img.shields.io/badge/MicroPython-2B2728?style=for-the-badge">

**Backend**

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white">
<img alt="EdgeDB" src="https://img.shields.io/badge/EdgeDB-111111?style=for-the-badge">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">

</div>

## Projects

<div align="center">

<a href="https://github.com/Igor20264/NodeMP-C_ABI-Python"><img src="assets/card-cpython.svg" alt="NodeMP CPython host: a global node, with heavy work on its own core" width="420"></a>
&nbsp;
<a href="https://github.com/Igor20264/NodeMP-C_ABI-micropython"><img src="assets/card-micropython.svg" alt="NodeMP MicroPython host: sandboxed scripts and a lane of their own" width="420"></a>

<br>

<a href="https://github.com/Igor20264/NodeMP-C_ABI-luajit"><img src="assets/card-luajit.svg" alt="NodeMP LuaJIT host: LuaJIT linked into the server module" width="420"></a>
&nbsp;
<a href="https://github.com/Igor20264/CRUD_test_task"><img src="assets/card-booking.svg" alt="Booking API: FastAPI, EdgeDB, and Docker" width="420"></a>

</div>

<br>

Also [Starter-Minecraft-Server](https://github.com/Igor20264/Starter-Minecraft-Server) — a small Python starter for a Minecraft server.

## GitHub

<div align="center">

<img alt="GitHub stats for Igor20264" width="400" src="https://github-readme-stats.vercel.app/api?username=Igor20264&show_icons=true&hide_border=true&hide_rank=true&bg_color=0f172a&title_color=7dd3fc&text_color=e2e8f0&icon_color=38bdf8">
&nbsp;
<img alt="Most used languages for Igor20264" width="340" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Igor20264&layout=compact&hide_border=true&exclude_repo=humorists-template&langs_count=2&bg_color=0f172a&title_color=7dd3fc&text_color=e2e8f0">

</div>

---

## По-русски

Я пишу на Python и учусь в РТУ МИРЭА в Москве. Python — основная работа. На C, C# и Lua перехожу, когда нужно подойти ближе к рантайму, к хосту языка или к небольшой утилите.

Сейчас это языковые модули NodeMP. Каждый из них — хост на C ABI: CPython, MicroPython или LuaJIT. Скрипт видит глобальный `node`, а долгая работа уходит с игрового тика на поток, закреплённый за одним ядром.

Из бэкенда есть небольшой сервис бронирования: FastAPI, EdgeDB и Docker, пользователи и слоты времени.

| Проект | Что это |
| --- | --- |
| [NodeMP · Python](https://github.com/Igor20264/NodeMP-C_ABI-Python) | Хост CPython. Скрипт видит `node`, тяжёлая работа сидит на своём ядре. |
| [NodeMP · MicroPython](https://github.com/Igor20264/NodeMP-C_ABI-micropython) | Отдельный интерпретатор рядом с CPython. Скрипты в песочнице, своя очередь задач. |
| [NodeMP · LuaJIT](https://github.com/Igor20264/NodeMP-C_ABI-luajit) | LuaJIT вшит в модуль сервера. Отдельный `lua51.dll` серверу не нужен. |
| [Booking API](https://github.com/Igor20264/CRUD_test_task) | Бронирование слотов времени. FastAPI, EdgeDB и Docker. |
| [Starter-Minecraft-Server](https://github.com/Igor20264/Starter-Minecraft-Server) | Небольшой запуск сервера Minecraft на Python. |
