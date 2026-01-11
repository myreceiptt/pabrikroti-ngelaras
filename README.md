# PABRIK ROTI [![version](https://img.shields.io/badge/version-2.1.11.1-blue)](https://github.com/myreceiptt/pabrikroti-ngelaras/releases/tag/v.2.1.11.1)

> "This is not just a factory. This is a rehearsal of freedom—kneaded with code, fermented by its community, and baked through the heat of shared struggles."
>
> — Prof. NOTA

---

---

## Maintenance by Prof. NOTA Evergreen Standard

This repo is a **Live Artefact App**: the user-facing UX is intentionally frozen
("MINT CLOSED", no wallet prompts), while the codebase remains buildable and
production-safe on Vercel.

### Runtime

- Node: **24.x** (local + Vercel)
- Package manager: **Yarn** (lockfile: `yarn.lock`)
- Deploy target: **Vercel**

### Build System

- Next.js **16** (Turbopack)

### Monthly Safe Updates (recommended)

Monthly is **monitor + verify**, not modernization.

1. Check what’s outdated (report only):

   - `yarn outdated`

2. Security report (report only unless explicitly approved):

   - `yarn audit --level moderate`

3. Verify build reproducibility:

   - `yarn lint`
   - `yarn build`

4. Verify production sanity:

   - Confirm "MINT CLOSED"
   - Confirm no wallet prompts / connect flows
   - Confirm no critical console errors

### Major Updates (quarterly / scheduled)

Major upgrades must be done **one at a time**, with a dedicated PR and full testing.
Artefact UX must remain unchanged.

Examples:

- React major version upgrade
- Web3 stack upgrade (e.g., web3 v1 → v4)
- Toolchain changes
- Node major policy change

### Artefact UX Policy (Frozen)

- Minting must remain **disabled**
- Wallet connect must remain **disabled**
- Any functional change requires a versioned successor (new tag/release)

---

---

## PABRIK ROTI v.2.1.11: Staging NFT Indonesia by Ngelaras Roso

Link #1: [www.ngelarasroso.id](https://www.ngelarasroso.id/)  
Link #2: [ngelaras.endhonesa.com](https://ngelaras.endhonesa.com/)

🧬 Forked from [PABRIKROTI-MASTER](https://github.com/myreceiptt/pabrikroti-master/releases/tag/v.2.1.11-ngelaras)

## 📜 License

This project is licensed under a **Custom Limited License** by [Prof. NOTA & Prof. NOTA Inc.](https://nota.endhonesa.com/).

- 🏛️ [English (UK)](./licenses/LICENSE_UK.md)
- 🇮🇩 [Bahasa Indonesia](./licenses/LICENSE_ID.md)
- 🇺🇿 [Oʻzbekcha](./licenses/LICENSE_UZ.md)
- 🇭🇰 [Cantonese – Hong Kong](./licenses/LICENSE_HK.md)
- 🇲🇾 [Bahasa Malaysia](./licenses/LICENSE_MY.md)
- 🇦🇪 [العربية – الإمارات](./licenses/LICENSE_AE.md)

> 📩 For permission or inquiries, contact: [nota@endhonesa.com](mailto:nota@endhonesa.com)

## Usage

### Install dependencies

```bash
yarn
```

### Check outdated dependencies

```bash
yarn up -i
```

### Upgrade dependencies interactively

```bash
yarn up -i
```

### Start development server

```bash
yarn dev
```

### Check all the code

```bash
yarn run lint
```

### Create a production build

```bash
yarn build
```

### Preview the production build

```bash
yarn start
```

## Resources

- [Prof. NOTA Inc.](https://nota.endhonesa.com/)
- [Prof. NOTA Console](https://prompt.endhonesa.com/)
- [Prof. NOTA Tutor](https://baca.endhonesa.com/)

## Join Prof. NOTA Discord

For questions or suggestions, join Prof. NOTA discord at [https://discord.gg/5KrsT6MbFm](https://discord.gg/5KrsT6MbFm).
