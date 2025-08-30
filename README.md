# Take Ownership Context Menu

This repository contains registry hacks to add or remove the **Take Ownership** option from the context menu in Windows. This feature allows you to take control of files and folders that are otherwise protected by the TrustedInstaller or User Account Control (UAC), enabling you to open, delete, move, or rename them.

### **Why Use This?**
- Gain full control over files and folders that are inaccessible.
- Manage files on external or secondary hard drives, especially photos.
- Simplify ownership changes with a single right-click.

## **Features**
1. **Add Take Ownership Option**  
   Enables the "Take Ownership" option in the context menu for easy access.  

2. **Remove Take Ownership Option**  
   Restores the context menu to its default state by removing the "Take Ownership" option.

## Files Included
1. **`Add Take Ownership to Context Menu.reg`**  
   Adds the "Take Ownership" option to the right-click context menu.

2. **`Remove Take Ownership from Context Menu (Default).reg`**  
   Removes the "Take Ownership" option, restoring the default context menu behavior.

## **How to Use**
### Step 1: Add "Take Ownership" Option
1. Download the `Add Take Ownership to Context Menu.reg` file.
2. Double-click the file to merge it into the Windows Registry.
3. Confirm any prompts to make the changes.

### Step 2: Remove "Take Ownership" Option (Optional)
1. Download the `Remove Take Ownership from Context Menu (Default).reg` file.
2. Double-click the file to remove the "Take Ownership" option.
3. Confirm any prompts to revert the changes.

## **Warning**
- Modifying the Windows Registry can have unintended consequences if done incorrectly. Always back up your registry before making any changes.
- Use this tool responsibly and only on files or folders you need to access.

## **License**
This project is licensed under the [MIT License](LICENSE).

## **Disclaimer**
This project is provided **for educational and demonstrational purposes only**.  
The author is **not responsible for any loss, damage, or misuse** resulting from the use of this program.  
Use entirely at your own risk.

## **Credits**
Tool skidded from [MajorGeeks](https://www.majorgeeks.com/content/page/take_full_ownership_of_files_folders.html).