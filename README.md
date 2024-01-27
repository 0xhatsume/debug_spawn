### Setup Params and Steps after npx create

**Steps In Contracts Folder (dojo-starter)**
1. `cd dojo-starter && katana --disable-fee`
2. `sozo build && sozo migrate`
3. world address is : `0x28f5999ae62fec17c09c52a800e244961dba05251f5aaf923afabd9c9804d1a`
4. `sh ./scripts/default_auth.sh`
5. `torii --world 0x28f5999ae62fec17c09c52a800e244961dba05251f5aaf923afabd9c9804d1a`

**Steps In Front-End Client Folder (react-app)**
6. update front-end folder .env with all params from katana and world address
7. update package.json's create-components cmd with correct world address and path
8. update dojoConfig.ts with correct import path
9. `pnpm install`
10. `pnpm run create-components`
11. `pnpm run dev`

**Steps In Browser**
12. Clear all cache and clear all burners.
13. Click `create burner` and ensure console has no errors.
14. Click `spawn`.