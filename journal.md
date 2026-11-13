# AI Engineering Prep - Journal

## Template
### YYYY-MM-DD - Week XX, Day X
- **Did:** 
- **Learned:** 
- **Explain-aloud check:** (topic, recording file name, how it went)
- **Stuck on:** 
- **Tomorrow:** 

@"

### 2026-11-13 - Week 00, Day 0 (Setup)
- **Did:** Set up the dev environment. Python 3.13, VS Code, Git and Docker were already installed (kept 3.13 instead of 3.12). Created an SSH key and linked it to GitHub. Created this repo with week01-week08 folders and the journal. Signed up for LeetCode and AWS (Free plan). Created a Claude API key. Turned off Copilot and AI autocomplete in VS Code. Set up Sound Recorder for explain-aloud checks.
- **Learned:** AWS sign-in has two paths: root user (email) and IAM user (account ID + username); a new account uses root. New Claude Console keys start with sk-ant-usr- and needed an updated SDK. python-dotenv does not override an existing env variable. .gitignore keeps .env (and my key) out of a public repo; checked with git check-ignore -v .env.
- **Explain-aloud check:** n/a (setup day)
- **Stuck on:** API key gave "Could not resolve authentication method", then 401 invalid x-api-key. Fixed by putting the key in .env with VS Code and upgrading the anthropic SDK.
- **Tomorrow:** Start Week 1 on Monday 16 Nov. Before then: turn on AWS root MFA and delete the old unused API key.

---
"@
