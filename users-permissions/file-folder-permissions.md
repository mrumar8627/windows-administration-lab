# File and Folder Permissions

## Objective

To understand basic Windows file and folder permissions and how they control access to data.

## What Are File and Folder Permissions?

File and folder permissions determine what users can do with files and folders.

Permissions can control whether a user can:

- Read a file
- Create or add files
- Modify files
- Delete files
- Execute a file

Permissions are important for protecting data and preventing unauthorized changes.

## Common NTFS Permissions

Common Windows NTFS permissions include:

| Permission | Description |
|---|---|
| Read | View files and folders |
| Write | Create or modify files |
| Read & Execute | Read files and run executable programs |
| Modify | Read, write, modify, and delete files |
| Full Control | Full access including changing permissions |

## Checking Folder Permissions

To check the permissions of a folder:

1. Right-click the folder.
2. Select **Properties**.
3. Open the **Security** tab.
4. Select a user or group.
5. Review the permissions shown.

## Example

Suppose a school computer contains a folder:

`C:\SchoolData`

The IT administrator may configure permissions so that:

- Teachers can read and modify files.
- Students can read files.
- Administrators have full control.

This helps protect important school data.

## Changing Permissions

To change permissions:

1. Right-click the folder.
2. Select **Properties**.
3. Open the **Security** tab.
4. Select the required user or group.
5. Click **Edit**.
6. Select the appropriate permissions.
7. Click **Apply**.
8. Click **OK**.

Permissions should only be changed when there is a valid reason.

## Least Privilege

Users should receive only the permissions they need to perform their work.

For example:

A student who only needs to view a document should normally have **Read** access rather than **Full Control**.

This principle is called **least privilege**.

## Basic Troubleshooting

If a user cannot access a file or folder:

1. Confirm that the file or folder exists.
2. Check the user's account.
3. Open the Security tab.
4. Review the user's permissions.
5. Check whether the user belongs to the required group.
6. Confirm that the correct permissions are assigned.
7. Test access again.

## Important Note

Changing permissions incorrectly can prevent users from accessing important files.

Permissions should be changed carefully and according to organizational procedures.

## Learning Outcome

After completing this lab, I can:

- Explain file and folder permissions
- Identify common NTFS permissions
- Check Windows folder permissions
- Understand user and group access
- Apply the principle of least privilege
- Troubleshoot basic access problems
