# I18N-NG-Serve-NF-Issue

This repository's purpose is to demonstrate an issue with serving localized builds with @angular-architects/native-federation.
The issue occurs appears after moving from @angular/build version 20.3.6 => 20.3.7.


## Commands

```shell
npm run start:shell
```

```shell
npm run start:shell:fr
```

```shell
npm run start:shell:de
```

## Compatibility Table

| Command              | @angular/build 20.3.6 | @angular/build 20.3.7 |
|----------------------|-----------------------|-----------------------|
| `npm run start:shell` | ✅                 | ✅                 |
| `npm run start:shell:fr` | ✅              | ❌                 |
| `npm run start:shell:de` | ✅              | ❌                 |
