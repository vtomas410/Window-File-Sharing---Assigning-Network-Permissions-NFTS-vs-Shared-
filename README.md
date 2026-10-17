# Window File Sharing - Assigning Network Permissions (NFTS vs Shared)

Objectives:

- Understand the importance of file sharing in a networked environment.
- Learn how to share files and folders effectively.
- Differentiate between network sharing types and their use case.
- Understand how permissions control user access to shared files.
- Learn how to access shared folders efficiently.

---

File And Folder Sharing Types:

- Local: Sharing files and folders on the same local network
- Network: sharing files and folders across multiple computers within a network.

---

File And Folder Sharing Permissions

- NFTS: formatted with the NTFS file system
- Share: Network Level control System

NTFS permissions control file and folder access for both local and network users, while share permissions only apply to users connecting across a network.

Both can be used at the same time, but keep in mind the most restrictive applies.

---

Explicit vs. Inherited Permissions

- Explicit: Explicit permissions are access rights directly assigned to a specific file or folder
- Inherited: Automatically passed down, Inherited the permissions set on the parent folder by default. This can also be disabled.

---

Sharing Methods

- Mapped: A folder can be mapped to a drive letter on a user’s computer.
- Network: access it via a network path.

---

Activity 1: 

A marketing intern needs access to the marketing team’s shared folder “Marketing” to view content but should not modify or delete files.

Step 1: Open new Finder folder → Click this PC → This PC → Local Disk

Step 2: Right click “Marketing” → click properties

Step 3: Click on Security tab or Sharing tab

Step 4: Click share the folder

Step 5: Click edit → Click add → Add Marketing interns → Click ok → Select marketing interns and allow only Read option

Step 6: Click okay and apply.

---

Activity 2:

The Hr Department needs a secure folder “HRGroup” That only HR staff can access. Other employees should not see the folder at all.

Step 1: Open new Finder folder → Click this PC → This PC → Local Disk

Step 2: Right click “HR group” → click properties

Step 3: Click on Sharing tab

Step 4: Click share the folder

Step 5: click Permissions

Step 6: Select “Everyone” → Remove user/group

Step 7: Add HR Staff → Click ok → allow full control

Step 8: Click on security (NFTS) → Advance Sharing → Share Name → click HR group.

Step 9: Add “HR Staff” → Allow full control

Step 10: Click OK and Apply.

---

Activity 3:

A third-party vendor needs access to a temporary folder **VendorFiles** to upload reports but should not see other files.

Step 1: Open new Finder folder → Click this PC → This PC → Local Disk

Step 2: Right click “Vendor files” → click properties

Step 3: Click on Sharing tab

Step 4: Click share the folder

Step 5: click Permissions

Step 6: Add “Vendor” → Allow full control → Click apply and ok

Step 7:  Click on security (NFTS) → Click edit → Click Add → Add “Vendor” → Click ok and apply.

Step 8: Select only “Write”.

---

Activity 4:

In the IT Department, all techs need access to the Software Repository **Software** but only senior IT staff should be able to access the “Licenses” subfolder

Step 1: Open new Finder folder → Click this PC → This PC → Local Disk

Step 2: Right click “Software” → click properties

Step 3: Click on Sharing tab → Advance sharing

Step 4: Click share the folder

Step 5: click Permissions

Step 6: Click add → add IT-department → Click okay → Allow full control → click okay and apply.

Step 7: Click software folder →  Right click “Licenses” → click properties → click security. (This folder has inherited permissions from software)

Step 8: Right click “License” → click properties → Click Advance → Disable inheritance.

Step 9: Click edit → add “Senior IT” → Allow full Control

Step 10: Click okay and apply.

Step 11: Verify by creating a new folder and checking Security tab (NFTS), Should be default permissions.
