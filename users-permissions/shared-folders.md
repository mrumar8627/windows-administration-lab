# Windows Shared Folders

## Objective

To understand how Windows shared folders allow users to access files over a local network.

## What Is a Shared Folder?

A shared folder is a folder that can be accessed by other computers or users over a network.

Shared folders are commonly used in offices, schools, and other organizations to provide access to common files.

## Example

A school may have a shared folder containing teaching resources:

`\\School-PC\TeachingResources`

Teachers connected to the same network may access the shared folder according to their assigned permissions.

## Creating a Shared Folder

Basic steps to share a folder:

1. Create or select a folder.
2. Right-click the folder.
3. Select **Properties**.
4. Open the **Sharing** tab.
5. Select **Advanced Sharing**.
6. Enable **Share this folder**.
7. Configure the share name.
8. Configure permissions if required.
9. Apply the settings.

## Accessing a Shared Folder

A shared folder can be accessed using a network path.

Example:

`\\ComputerName\SharedFolder`

You can enter the network path in File Explorer's address bar.

## Checking the Computer Name

To find the computer name:

1. Open **Settings**.
2. Go to **System**.
3. Select **About**.
4. Check **Device name**.

The device name can be used as part of the network path.

## Sharing Permissions

Sharing permissions control what users can do when accessing a folder through the network.

Common access levels include:

- Read
- Change
- Full Control

Access should be configured according to the user's requirements.

## NTFS and Sharing Permissions

Windows can apply both:

- Share permissions
- NTFS permissions

When a user accesses a folder over the network, both types of permissions can affect access.

The most restrictive effective permission normally determines what the user can do.

## Basic Troubleshooting

If a shared folder cannot be accessed:

1. Check that both computers are connected to the network.
2. Confirm the computer name.
3. Check the network path.
4. Confirm that the folder is still shared.
5. Check sharing permissions.
6. Check NTFS permissions.
7. Check Windows network settings.
8. Test the connection again.

## Example Troubleshooting Scenario

### Problem

A teacher cannot access:

`\\School-PC\TeachingResources`

### Checks

The IT support technician checks:

- Network connection
- Computer name
- Shared folder availability
- Sharing permissions
- NTFS permissions

### Possible Cause

The teacher may not have the required permissions to access the shared folder.

### Action

The appropriate permissions can be assigned according to the organization's access policy.

## Security Considerations

Shared folders should be configured carefully.

Avoid giving **Full Control** access when users only need to read or modify files.

Only authorized users should have access to sensitive information.

## Documentation

A basic shared-folder record can include:

Shared Folder:
Computer Name:
Share Name:
Users / Groups:
Permissions:
Purpose:
Date:
Notes:

Do not record passwords or other sensitive authentication information.

## Learning Outcome

After completing this lab, I can:

- Explain what a shared folder is
- Create a basic Windows shared folder
- Access a shared folder using a network path
- Understand sharing permissions
- Understand the relationship between NTFS and sharing permissions
- Troubleshoot basic shared-folder access problems
- Apply basic security principles
