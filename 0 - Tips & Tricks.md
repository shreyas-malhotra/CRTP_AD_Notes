- Run BloodHound legacy for better compatibility with the exam environment.
- Run BloodHound on your host machine, not the student VM, since it will slow down the VM.
- Have your tools ready in a zip file before the exam so that they are easily transferrable to the student VM.
- Make sure that the tools do not get detected by Windows Defender, since the AVs deployed in the exam environment are completely up to date; obfuscate the tools/payload if necessary.
- Use HFS - HTTP File Server, wherever required.

Useful websites I found:
- https://wadcoms.github.io/
- https://zer1t0.gitlab.io/posts/attacking_ad/
- https://0xd4y.com/2023/04/05/CRTP-Notes/
- https://0xd4y.com/misc/CRTP_Notes.pdf
- https://dudisamarel.gitbook.io/crtp-notes
- https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse
- https://casvancooten.com/posts/2020/11/windows-active-directory-exploitation-cheat-sheet-and-command-reference/
- https://swisskyrepo.github.io/InternalAllTheThings/

Useful blogs I found:
- https://medium.com/@dineshkumaar478
- https://medium.com/@dineshkumaar478/my-crtp-journey-2025-how-i-passed-lessons-learned-e8b1305e830c
- https://happycamper84.medium.com/thm-walkthrough-list-ad-stuff-95280f400bec

### Practise Questions using GOAD-light
- The Road to CRTP Cert — Part 10
	- Questions
		- Enumerate all users in the **north.sevenkingdoms.local** domain.
		- Enumerate all computers in the **north.sevenkingdoms.local** domain.
		- Enumerate all Domain Administrators in the **north.sevenkingdoms.local** domain.
		- Enumerate all Enterprise Administrators in the **north.sevenkingdoms.local** domain.
		- Enumerate all shared resources in the **north.sevenkingdoms.local** domain.
		- Enumerate all Organizational Units (OUs) in the **north.sevenkingdoms.local** domain.
		- Enumerate all computers within the Domain Controllers OU in the **north.sevenkingdoms.local** domain.
		- Enumerate all Group Policy Objects (GPOs) in the **north.sevenkingdoms.local** domain.
		- Enumerate all GPOs applied to the Domain Controllers OU in the **north.sevenkingdoms.local** domain.
		- List Access Control List (ACL) permissions for the **Users** group.
		- List ACL permissions for the **Domain Admins** group.
		- List all modify rights and permissions for the specified user (samwell.tarly) or group (DNSAdmins).
		- Enumerate all domains within the **sevenkingdoms.local** forest.
		- Map trust relationships of the **north.sevenkingdoms.local** domain.
		- Map external trusts within the **sevenkingdoms.local** forest.
		- Identify and enumerate external trusts for the **north** domain. Can you enumerate trusts for a trusting forest?
		- Set up BloodHound and identify the shortest path to Domain Admins in the **north** domain.
	- Solutions:
		- https://medium.com/@dineshkumaar478/the-road-to-crtp-cert-part-10-c7b58a21ccca