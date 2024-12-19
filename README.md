# Bookmarklet Snippets

Quickly select, copy and paste text that you use often. It's simply a bookmark that shows you a list of text snippets.

![msedge_YDYCdXPXPS](https://github.com/user-attachments/assets/c4a538eb-c743-40e2-b767-df5e28f6b42a)


## What it does

- Shows a window with your saved texts
- Clicking a text copies it to your clipboard
- Shows a message when text is copied
- Easy to set up and use
- You can change the texts anytime

## Setting it up

1. Create a text file with your snippets (see example below)
2. Put this file on GitHub, Pastebin or your own server.
3. Show your browser's bookmark bar if it's hidden:
   - Chrome/Edge: Press Ctrl+Shift+B (or ⌘+Shift+B on Mac)
   - Firefox: Right-click the top of the browser and check "Bookmarks Toolbar"
4. Create the bookmark:
  Right-click your bookmark bar, select "Add new bookmark", name it "Text Snippets", and paste the code from `bookmarklet.js` into the URL field
5. In the bookmark code, change the `TEXT_URL` to point to your text file (has to be publicly visible so don't add confidential information in it.)

## How to use it

1. Click the bookmark whenever you need your saved texts
2. Choose the text to copy it
3. Paste it wherever you need it

## Creating your text file

Name your file `standardtexts.txt` and write it like this:

```
## E-mail 

### Greeting
Hello,

Thank you for your message. I hope you're having a great day.

### Response Delay
I apologize for the delayed response.

I've been out of office but am now back and ready to help you.

### Signature
Best regards,
John Smith
Senior Developer

### Let me know
Just let me know if there's anything else I can help you with.

## Inspections

### Reservations
This inspection report is based on assumptions about the underlying materials. After Demolition the estimates may have to be revised.

### Lorem
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tincidunt libero sed ante maximus, in convallis sem hendrerit. Aenean pulvinar, ante in dignissim cursus, tellus magna tempus augue, eu vulputate mauris nisi eu risus. 

## Courses

### Sign up
Sign up for paid courses here:

You can also order customized in-house training there.

### Webinars
See a list of future free webinars here:

```

Formatting rules:
- Any categories start with `##`
- Start each text with `### ` and a title
- Put your actual text below the title
- Leave empty lines between different texts

## Making changes

### Use your own texts
1. Create your text file like shown above
2. Upload it to GitHub, Pastebin or Nextcloud.
3. Get the public or raw link to your file (the file must be accessible by everyone)
4. Change the `TEXT_URL` in the bookmark code to your link

## Does it work in my browser?

Works in all modern browsers:
- Firefox
- Vivaldi
- Brave
- Chrome
- Edge
- Safari

## Does it work on all sites?

It should work on most sites, but some like outlook.com will block it from getting the list of snippets.

## Need help?

If something's not working:
1. Make sure your text file follows the format exactly and is public
2. If you are using Github check that you're using the "raw" GitHub link
3. Try copying and pasting the bookmark code again

Feel free to ask questions or suggest improvements!
