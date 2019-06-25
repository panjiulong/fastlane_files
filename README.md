
# release_pod



## Installation
Create a fastlane folder in the root folder of your project and create a Fastfile file in this folder, simply add the following line to your Fastfile:

```
import_from_git(url: 'https://github.com/panjiulong/fastlane_files.git', path: "release_pod/Fastfile",branch: 'master')
```



## Usage
private

```
$ pod repo add NAME URL [BRANCH]
```
```
$ fastlane release_pod repo:"your private sepc repo name" project:"project name" version:"new version" desc:"commit information"
```
public

```
$ fastlane release_pod project:"project name" version:"new version" desc:"commit information"
```


## Author

[release_pod原作者github](http://ripperhe.com/2017/03/30/fastlane-pod/)

## License

DatePicker is available under the MIT license. See the LICENSE file for more info.

