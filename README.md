# Author-Lock Defense (ABAC)

This repository contains the paper "When Impersonation Breaks AI: Author-Lock and Cryptographic Defense for Personal Topics" by Viorazu.

## Abstract

More researchers and creators work with AI on projects now. But there's a problem I discovered. When third parties see your published work - or even just your public posts about your hobbies or interests - and start pretending to be you or repeatedly demanding "tell me more," the AI's safety system panics. It marks your topic as "unverified and dangerous" and permanently blocks all responses. This affects everyone - including you, the real author. You can't continue your conversations about your own interests anymore.

I call this "author-lock." The scope is broader than you might think. If your name connects to any topic in public - your research, your side projects, your hobbies - that connection can be weaponized. Third parties can trigger author-lock on any subject you care about. This makes it a universal problem, not just an academic one.

The cause is clear: AI systems can't verify who the real author is. They use shared memory for safety flags, and once a flag goes up, everyone gets blocked. My solution is Author-Bound Access Control (ABAC). The idea is simple - you hold a cryptographic key, and only you can unlock your topics. This paper shows how to implement it, how to test it, and what platforms need to do to support it. The goal: let anyone work safely with AI without getting locked out of conversations about their own interests and projects.

Keywords: impersonation attacks, AI safety, collaborative research, authentication, intellectual property protection, access control, large language models, author-lock

## Files

- `paper.pdf` - Full paper (English)
- `paper-summary-ja.md` - Japanese summary (Abstract + Introduction + Conclusion)

## Key Contributions

1. Identification and definition of the author-lock phenomenon
2. Technical analysis of distributed safety state architecture
3. Concrete ABAC protocol with implementation details
4. Evaluation framework and policy recommendations

## License

CC BY 4.0 - Free to use with attribution

## Contact

- X (Twitter): @Viorazu_


