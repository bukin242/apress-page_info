# Apress::PageInfo

<a href="http://dolly.railsc.ru/projects/181/builds/latest/?ref=master"><img src="http://dolly.railsc.ru/badges/abak-press/apress-page_info/master" height="18"></a>

title, header, description, keywords для веб страницы

## Gem Releasing

### Правила версионирования:

http://semver.org

### Если релизим находясь в форке:

0. должны быть права на push в upstream
1. git checkout master
2. git pull upstream master
3. правим версию гема в файле VERSION в корне гема. (читаем правила версионирования)
4. rake release
5. git push upstream master
6. git push --tags upstream

## Contributing

1. Fork it ( https://github.com/abak-press/apress-page_info/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'feature(scope): comment \n\n Closes NN-123'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
