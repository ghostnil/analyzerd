# Analyzerd V2
Tool to get as much indexed information as possible to try to bypass WAFS

## [+] REQUIREMENTS [+]

```
Ruby 2.3.1 ~ 2.5.0
$ gem install bundle
$ bundle install
```

###### [-] API account Create links [-]

```
https://www.shodan.io/
https://viewdns.info/api
https://censys.io/
https://www.zoomeye.org/
```

#### [+] USAGE [+]:
```
  $ ruby analyzerD.rb -u https://target.com --all  --> All apis gathering
  $ ruby analyzerD.rb -u https://www.target.com -s --> only shodan
  $ ruby analyzerD.rb -u https://www.target.com -d --> only viewdns
  $ ruby analyzerD.rb -u https://www.target.com -c --> only censys
  $ ruby analyzerD.rb -u https://www.target.com -z --> only zoomeye
```

![](https://github.com/ghostnil/analyzerd/blob/master/analyzerd_true.gif)






# TODO

```
1 - fofa.so api
2 - HTML output
```
