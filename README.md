<p align="center">
  <a href="https://talaikis.com/">
    <img alt="Talaikis Ltd." src="https://github.com/TalaikisInc/talaikis.com_react/blob/master/media/logo.png" width="228">
  </a>
</p>

# Frontend Next 5.0

## Features

Fully featured React.js SSR user management system/ CMS (frontend).

* Passwordless user sign in, sign up
* Sign out
* Profile edit, delete
* Admin system (required password upon access)
* Passwordless account confirm
* Written in React hooks
* Atomic (in progress anyway) design. Currently, if changing nothing else, color scheme can be changed via one config file.
* Encrypted user browser storage

## Backend

* [API Next](https://github.com/TalaikisInc/api-next) - an API on AWS

## Install

```bash
npm i
```

## Add secrets

```bash
now secrets add cms-api-key <key>
# ...
```

## Build

```bash
npm run build
```

## Start

```bash
# Development:
npm run dev

# Production
npm run build
npm run start
```

## Get it

API Next + Frontend Next is a boilerplate for custom products. If you want to discuss the system, please contact me via [form](https://www.talaikis.com/).

## Licence

MIT
