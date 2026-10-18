<div align="center">

<img src="assets/banner.svg" alt="Igor — Python developer, Moscow" width="100%">

Python first. C, C++, and Lua when the runtime needs a closer look.

</div>

## About

I am a Python developer in Moscow. Python is home base. C, C++, C#, and Lua are how I get closer to a runtime, a host, or a small tool that should stay out of the way.

Right now that means language modules for [NodeMP](https://github.com/Igor20264/NodeMP-C_ABI-Python). CPython, MicroPython, LuaJIT, Luau, QuickJS, Squirrel, and Wren each sit on the C ABI. Scripts talk to the server through a global `node`, and long work can leave the game tick and run on a thread pinned to one core.

On the backend I built a small booking service: FastAPI, EdgeDB, and Docker, with users and time-slot reservations.

## Stack

<div align="center">

**Languages**

<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img alt="C" src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
<img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white">
<img alt="Lua" src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white">
<img alt="Luau" src="https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img alt="MicroPython" src="https://img.shields.io/badge/MicroPython-2B2728?style=for-the-badge">

**Runtimes**

<img alt="CPython" src="https://img.shields.io/badge/CPython-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img alt="LuaJIT" src="https://img.shields.io/badge/LuaJIT-000080?style=for-the-badge&logo=lua&logoColor=white">
<img alt="QuickJS" src="https://img.shields.io/badge/QuickJS-6CA6CD?style=for-the-badge">
<img alt="Squirrel" src="https://img.shields.io/badge/Squirrel-8B4513?style=for-the-badge">
<img alt="Wren" src="https://img.shields.io/badge/Wren-5B4B8A?style=for-the-badge">
<img alt="Mojo" src="https://img.shields.io/badge/Mojo-FF8C00?style=for-the-badge">

**Build**

<img alt="CMake" src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white">
<img alt="GCC" src="https://img.shields.io/badge/GCC-000000?style=for-the-badge&logo=gcc&logoColor=white">
<img alt="MinGW" src="https://img.shields.io/badge/MinGW-3C6EAE?style=for-the-badge">
<img alt="Make" src="https://img.shields.io/badge/Make-427819?style=for-the-badge">
<img alt="TOML" src="https://img.shields.io/badge/TOML-9C4221?style=for-the-badge">
<img alt="Windows" src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
<img alt="macOS" src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white">

**Backend**

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white">
<img alt="Uvicorn" src="https://img.shields.io/badge/Uvicorn-499848?style=for-the-badge">
<img alt="EdgeDB" src="https://img.shields.io/badge/EdgeDB-111111?style=for-the-badge">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">

**Docs**

<img alt="Astro" src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white">
<img alt="Starlight" src="https://img.shields.io/badge/Starlight-8D46E7?style=for-the-badge">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">

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

---

## По-русски

Я пишу на Python. Москва. Python — основная работа. На C, C++, C# и Lua перехожу, когда нужно подойти ближе к рантайму, к хосту языка или к небольшой утилите.

Сейчас это языковые модули NodeMP: CPython, MicroPython, LuaJIT, Luau, QuickJS, Squirrel и Wren. Каждый из них — хост на C ABI. Скрипт видит глобальный `node`, а долгая работа уходит с игрового тика на поток, закреплённый за одним ядром.

Из бэкенда есть небольшой сервис бронирования: FastAPI, EdgeDB и Docker, пользователи и слоты времени.

| Проект | Что это |
| --- | --- |
| [NodeMP · Python](https://github.com/Igor20264/NodeMP-C_ABI-Python) | Хост CPython. Скрипт видит `node`, тяжёлая работа сидит на своём ядре. |
| [NodeMP · MicroPython](https://github.com/Igor20264/NodeMP-C_ABI-micropython) | Отдельный интерпретатор рядом с CPython. Скрипты в песочнице, своя очередь задач. |
| [NodeMP · LuaJIT](https://github.com/Igor20264/NodeMP-C_ABI-luajit) | LuaJIT вшит в модуль сервера. Отдельный `lua51.dll` серверу не нужен. |
| [Booking API](https://github.com/Igor20264/CRUD_test_task) | Бронирование слотов времени. FastAPI, EdgeDB и Docker. |
| [Starter-Minecraft-Server](https://github.com/Igor20264/Starter-Minecraft-Server) | Небольшой запуск сервера Minecraft на Python. |
