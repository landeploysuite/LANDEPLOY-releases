# LANDEPLOY-releases

Official Release Ledger & Distribution Registry for **LANDeploy Server** & **LANDeploy Agent**.

## Live Ledger
- **URL**: [https://landeploy-releases.vercel.app](https://landeploy-releases.vercel.app)
- **Machine API**: [https://landeploy-releases.vercel.app/version.json](https://landeploy-releases.vercel.app/version.json)

## Update Automation
Every time LANDeploy Host Server or Client Agent launches, it queries `version.json` and GitHub Releases. If:
```text
current_version < latest_version
```
the application prompts the user and initiates an automatic download and installation.

## Releases
Find all compiled `.exe` releases under [Releases](https://github.com/landeploysuite/LANDEPLOY-releases/releases).
