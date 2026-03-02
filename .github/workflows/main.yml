const fs = require('fs');
if (fs.existsSync('config.env')) require('dotenv').config({ path: './config.env' });

function convertToBool(text, fault = 'true') {
    return text === fault ? true : false;
}
module.exports = {
SESSION_ID: process.env.SESSION_ID || "eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoic0FiNmEwZERiSW00dDJYRVpxNm5Ca2k2KzUvNE9qd0NwMFhGaE95ZmdYYz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiaDZxU3JpY1llem0yQUI0ZzBDYWMzTm5SQUx6QzRuTFFhWStqTUp4R2xBYz0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiI4S0RZb3JtdlNaOFBnbTFzV3RBTXlGRFRZYXN2enE4SWJsVnFVWDRJQ1hjPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJZNU9Sa3lmV2ZnUmxuMHFiZ2RoK3dLWG9iZFdsbTZ0amhwMjdHVmRiU2dnPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6Ik9IZUxWK0wvaE9wTjBWRjE0M1pLMXlISy9jQitRNHFCblRaWU10N2hwWGc9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6InJHMG1yK2lWa3hCTDNsS0orSjdrU0x2bEF5dktFTFZaTm9CdCtCcDVra2s9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiZ01TRVlIRVZ5MDlXUGFQQzZiRDlrS1Y1TW5RQjNzTWhRYnpnbitRWU8yOD0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiR0ZIeEh2Y2ZuZjNKbHhZVG1JbDdpVVUya041TGx5b1lWdWNlRlFTb2dWST0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IlkybGwvTE5mS2dnWXkwSkdNeXB5bWhpUXlGVkpvazFCdk13ZnF4WC90Nkh4L1Z1Slo3RkkwQWtncWFsWDNyQjI2QU5DY3lULyswbk02Ujg3ZENoNmdnPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MjAzLCJhZHZTZWNyZXRLZXkiOiJ3RFJ4OXFuMVZDYUlTYVRpa20zR21jOFF5eE5JTVNJTDVpS20zQXVqa21VPSIsInByb2Nlc3NlZEhpc3RvcnlNZXNzYWdlcyI6W10sIm5leHRQcmVLZXlJZCI6MzEsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjozMSwiYWNjb3VudFN5bmNDb3VudGVyIjowLCJhY2NvdW50U2V0dGluZ3MiOnsidW5hcmNoaXZlQ2hhdHMiOnRydWV9LCJyZWdpc3RlcmVkIjp0cnVlLCJwYWlyaW5nQ29kZSI6Ijk5MTRVTDZBIiwibWUiOnsiaWQiOiIyNTQxMTI1ODE4MTA6MTFAcy53aGF0c2FwcC5uZXQiLCJsaWQiOiIxODgwNzcyNzIyNDg1MjM6MTFAbGlkIn0sImFjY291bnQiOnsiZGV0YWlscyI6IkNOMlI0Y0lERU9UMWw4MEdHQVFnQUNnQSIsImFjY291bnRTaWduYXR1cmVLZXkiOiJCLzZWZXcxenNUOTVBV3Z4OW5WcDlVZ3dNN0huOFhXb2hjazhZMFlGNmkwPSIsImFjY291bnRTaWduYXR1cmUiOiJiaU16aWNETGRDYmpKSGZNQUl1eHlWeGFTdktXOEJ0TzMyR0pWbGt5WGFyTjExd25YdVZ6ellHVXdPQ2ZyUnBYa29Ka0pKYmxVYTFFWFdyMEhTUkVBZz09IiwiZGV2aWNlU2lnbmF0dXJlIjoic3Z0QkovUTVVZHdEd1A5d3hxSWlpSXJBUWJxWEhYMXhqVXVicTYwTFpGV2t3UFNpclU0Q0JBUDVsTEorTm1pdEZCTnRSTmJWS2hiZjVJU20zc1U1alE9PSJ9LCJzaWduYWxJZGVudGl0aWVzIjpbeyJpZGVudGlmaWVyIjp7Im5hbWUiOiIyNTQxMTI1ODE4MTA6MTFAcy53aGF0c2FwcC5uZXQiLCJkZXZpY2VJZCI6MH0sImlkZW50aWZpZXJLZXkiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJCUWYrbFhzTmM3RS9lUUZyOGZaMWFmVklNRE94NS9GMXFJWEpQR05HQmVvdCJ9fV0sInBsYXRmb3JtIjoiYW5kcm9pZCIsInJvdXRpbmdJbmZvIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQ0FVSURRZ0kifSwibGFzdEFjY291bnRTeW5jVGltZXN0YW1wIjoxNzcyNDg1MzYwLCJsYXN0UHJvcEhhc2giOiJQV2s1QiIsIm15QXBwU3RhdGVLZXlJZCI6IkFBQUFBTWdPIn0=",
// add your Session Id 
AUTO_STATUS_SEEN: process.env.AUTO_STATUS_SEEN || "false",
// make true or false status auto seen
AUTO_STATUS_REPLY: process.env.AUTO_STATUS_REPLY || "false",
// make true if you want auto reply on status 
AUTO_STATUS_REACT: process.env.AUTO_STATUS_REACT || "false",
// make true if you want auto reply on status 
AUTO_STATUS_MSG: process.env.AUTO_STATUS_MSG || "*𝚂𝙴𝙴𝙽 𝚈𝙾𝚄𝚁 𝚂𝚃𝙰𝚃𝚄𝚂 𝙱𝚈 𝙰𝙽𝙰𝚈𝙰𝚃-𝙰𝙸 🤍*",
// set the auto reply massage on status reply  
ANTI_DELETE: process.env.ANTI_DELETE || "false",
// set true false for anti delete     
ANTI_DEL_PATH: process.env.ANTI_DEL_PATH || "inbox", 
// change it to 'same' if you want to resend deleted message in same chat     
WELCOME: process.env.WELCOME || "false",
// true if want welcome and goodbye msg in groups    
ADMIN_EVENTS: process.env.ADMIN_EVENTS || "false",
// make true to know who dismiss or promoted a member in group
ANTI_LINK: process.env.ANTI_LINK || "false",
// make anti link true,false for groups 
MENTION_REPLY: process.env.MENTION_REPLY || "false",
// make true if want auto voice reply if someone menetion you 
MENU_IMAGE_URL: process.env.MENU_IMAGE_URL || "https://files.catbox.moe/adhn5v.jpg",
// add custom menu and mention reply image url
PREFIX: process.env.PREFIX || ".",
// add your prifix for bot   
BOT_NAME: process.env.BOT_NAME || "ANAYAT-AI",
// add bot namw here for menu
STICKER_NAME: process.env.STICKER_NAME || "ANAYAT-AI",
// type sticker pack name 
CUSTOM_REACT: process.env.CUSTOM_REACT || "false",
// make this true for custum emoji react    
CUSTOM_REACT_EMOJIS: process.env.CUSTOM_REACT_EMOJIS || "💝,💖,💗,❤️‍🩹,❤️,🧡,💛,💚,💙,💜,🤎,🖤,🤍",
// chose custom react emojis by yourself 
DELETE_LINKS: process.env.DELETE_LINKS || "false",
// automatic delete links witho remove member 
OWNER_NUMBER: process.env.OWNER_NUMBER || "923452401207",
// add your bot owner number
OWNER_NAME: process.env.OWNER_NAME || "𝙰𝙽𝙰𝚈𝙰𝚃 𝙷𝙰𝙲𝙺𝙴𝚁",
// add bot owner name
DESCRIPTION: process.env.DESCRIPTION || "*© ᴘᴏᴡᴇʀᴇᴅ ʙʏ 𝙰𝙽𝙰𝚈𝙰𝚃-𝙰𝙸 ❣️*",
// add bot owner name    
ALIVE_VID: process.env.ALIVE_VID || "https://files.catbox.moe/2myos8.mp4",
// add img for alive msg
LIVE_MSG: process.env.LIVE_MSG || "𝚉𝙸𝙽𝙳𝙰 𝙷𝚄𝙽 𝚈𝙰𝚁 🤖",
// add alive msg here 
READ_MESSAGE: process.env.READ_MESSAGE || "false",
// Turn true or false for automatic read msgs
AUTO_REACT: process.env.AUTO_REACT || "false",
// make this true or false for auto react on all msgs
ANTI_BAD: process.env.ANTI_BAD || "false",
// false or true for anti bad words  
MODE: process.env.MODE || "public",
// make bot public-private-inbox-group 
ANTI_LINK_KICK: process.env.ANTI_LINK_KICK || "false",
// make anti link true,false for groups 
AUTO_STICKER: process.env.AUTO_STICKER || "false",
// make true for automatic stickers 
AUTO_REPLY: process.env.AUTO_REPLY || "false",
// make true or false automatic text reply 
ALWAYS_ONLINE: process.env.ALWAYS_ONLINE || "false",
// maks true for always online 
PUBLIC_MODE: process.env.PUBLIC_MODE || "true",
// make false if want private mod
AUTO_TYPING: process.env.AUTO_TYPING || "false",
// true for automatic show typing   
READ_CMD: process.env.READ_CMD || "false",
// true if want mark commands as read 
DEV: process.env.DEV || "923452401207",
//replace with your whatsapp number        
ANTI_VV: process.env.ANTI_VV || "false",
// true for anti once view 
AUTO_RECORDING: process.env.AUTO_RECORDING || "false"
// make it true for auto recoding 
};
