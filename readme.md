# Data & AI Microsoft DFW User Group Repository

Welcome to the official home of the Data & AI Microsoft DFW User Group! Whether you’re a data engineer, scientist, analyst, ML practitioner, architect, or Azure enthusiast, this is your one-stop place to:
  
- Explore slide decks, demo code, and Jupyter notebooks  
- Access deployment templates and helper scripts for Azure Data & AI services  
- Watch recordings or follow along via curated resource links  

Our community gathers each month to learn, share real-world experiences, and build tomorrow’s intelligent solutions on the Microsoft Data & AI stack. 

---

## Upcoming Meetups & How to Join

Stay plugged in:

- ### [DFW Data & AI Meetup page](https://www.meetup.com/data-ai-microsoft/)
- ### [DFW Global AI Meetup page](https://www.meetup.com/amrobotics/)
- ### [LinkedIn Group](https://www.linkedin.com/groups/14518026/)

Join the conversation, propose talk ideas, or volunteer to present — everyone’s contribution makes our community stronger!
---

## Getting Started

This repository contains presentation decks and other large event files. Use a shallow clone to avoid downloading unnecessary Git history:

```bash
git clone --depth 1 https://github.com/giorgiosaez/meetup-data-ai.git
cd meetup-data-ai
```

If you only need files from one event, use a sparse clone to download that folder instead of the entire repository:

```bash
git clone --depth 1 --filter=blob:none --sparse https://github.com/giorgiosaez/meetup-data-ai.git
cd meetup-data-ai
git sparse-checkout set "20261012 - Global AI On Tour - Plano"
```

Replace the folder name in the last command with the event you need. Run `git sparse-checkout list` to see which folders are currently included.

### Clone Troubleshooting

If a full clone fails with an `RPC failed`, `early EOF`, or connection reset error:

1. Retry using the sparse-clone commands above.
2. Confirm that you are using a current [Git release](https://git-scm.com/downloads).
3. Try another network if a proxy, VPN, or firewall interrupts large downloads.
4. Open an issue with the full Git error message if the sparse clone also fails.

To add another event after a sparse clone, include all desired folders in one command:

```bash
git sparse-checkout set "20261012 - Global AI On Tour - Plano" "20260827 - Hands-on Global AI Construct Irving"
```

## Browsing Event Materials

1. Open the folder named for the event date and title.
2. Browse its README, presentation decks, code samples, and event photos when available.

---

## Contribution Guidelines

1. Create a top-level event folder named `YYYYMMDD - Event Name`.
2. Add a README and the event materials to that folder.
3. Submit a pull request describing your additions or updates.

We welcome improvements, corrections, translations, or any assets that enrich our community library!



---

## License
This project is licensed under the MIT License. See LICENSE for details. 
