# Bookmarklet Snippets

Quickly select, copy and paste text that you use often. It's simply a bookmark that shows you a list of text snippets.

## What it does

- Shows a window with your saved texts
- Clicking a text copies it to your clipboard
- Shows a message when text is copied
- Easy to set up and use
- You can change the texts anytime

## Setting it up

1. Create a text file with your snippets (see example below)
2. Put this file on GitHub
3. Show your browser's bookmark bar if it's hidden:
   - Chrome/Edge: Press Ctrl+Shift+B (or ⌘+Shift+B on Mac)
   - Firefox: Right-click the top of the browser and check "Bookmarks Toolbar"
4. Create the bookmark:
  Right-click your bookmark bar, select "Add new bookmark", name it "Text Snippets", and paste the code from `bookmarklet.js` into the URL field
5. In the bookmark code, change the `TEXT_URL` to point to your text file (has to be publicly visible so don't add confidentil information in it.

## How to use it

1. Click the bookmark whenever you need your saved texts
2. Choose the text to copy it
3. Paste it wherever you need it

## Creating your text file

Name your file `standardtexts.txt` and write it like this:

```
### Hello Message
Hi there!

Thanks for your message.

### Sorry I'm Late
Sorry for the late reply.

I was away from my desk.

### My Sign-off
Best regards,
John
```

Formatting rules:
- Start each text with `### ` and a title
- Put your actual text below the title
- Leave empty lines between different texts

## Making changes

### Use your own texts
1. Create your text file like shown above
2. Upload it to GitHub or Nextcloud, Onedrive, Dropbox or Gdrive.
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

## Need help?

If something's not working:
1. Make sure your text file follows the format exactly and is public
2. If you are using Github check that you're using the "raw" GitHub link
3. Try copying and pasting the bookmark code again

Feel free to ask questions or suggest improvements!
