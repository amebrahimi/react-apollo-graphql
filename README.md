# react-apollo-graphql
Doing some learning from this [Youtube Link](https://www.youtube.com/watch?v=m0TC5DcFHDY&list=PLLnpHn493BHFTDL9M1PKnxQwBwOZ8J-h4)

# Special thanks to LevelUpTuts 
![Logo](https://yt3.ggpht.com/a-/ACSszfF_2hzTBwVXh7UUXe5kqfgwvTqDdukcNhPwgA=s88-mo-c-c0xffffffff-rj-k-no)
</br>
</br>
[Scott Tolinski and Wes Boss Podcast](https://syntax.fm/)</br>
[LevelUpTuts Youtube Channel](https://www.youtube.com/channel/UCyU5wkjgQYGRB0hIHMwm2Sg)</br>

# Lets get started

Install ChoCho for `PowerShell`</br>
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
Install `Meteor`:
```
choco install meteor
```
Install bare `Meteor` App (Meteor with less packages):
```
meteor create apollo --bare
```

## Dependencies

```
npm install --save react react-dom
```
To Resolutions.graphql files work:
```
npm install --save-dev babel-plugin-inline-import
```