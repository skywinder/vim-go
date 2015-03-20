# Change Log

## [Unreleased](https://github.com/fatih/vim-go/tree/HEAD)

[Full Changelog](https://github.com/fatih/vim-go/compare/v1.0.3...HEAD)

**Closed issues:**

- gofmt spaces [\#360](https://github.com/fatih/vim-go/issues/360)

- Manual install not completely working [\#359](https://github.com/fatih/vim-go/issues/359)

- Saving files using CGO blocks. [\#358](https://github.com/fatih/vim-go/issues/358)

- Not an editor command: Fmt [\#357](https://github.com/fatih/vim-go/issues/357)

- Vim hangs on saving when the package is large [\#356](https://github.com/fatih/vim-go/issues/356)

- Compile error chevrons not showing when I upgrade to go1.4.2 [\#354](https://github.com/fatih/vim-go/issues/354)

- Don't allow gorename with unsaved changes [\#352](https://github.com/fatih/vim-go/issues/352)

- Is there any way I can get call hierarchy of a method like eclipse? [\#350](https://github.com/fatih/vim-go/issues/350)

- Not an Editor Command: GoDoc, GoBuild, GoRun [\#346](https://github.com/fatih/vim-go/issues/346)

## [v1.0.3](https://github.com/fatih/vim-go/tree/v1.0.3) (2015-03-07)

[Full Changelog](https://github.com/fatih/vim-go/compare/v1.0.2...v1.0.3)

**Fixed bugs:**

- Unable to specify multiple oracle scope locations [\#324](https://github.com/fatih/vim-go/issues/324)

- Vim helptags E154: Duplicate Tag after PR\#319 [\#323](https://github.com/fatih/vim-go/issues/323)

**Closed issues:**

- Call "go test -c" if :GoBuild is invoked on a test file [\#337](https://github.com/fatih/vim-go/issues/337)

- Highlighting user-defined functions  [\#336](https://github.com/fatih/vim-go/issues/336)

- Syntax highlighting issue [\#334](https://github.com/fatih/vim-go/issues/334)

- :GoDef working for everything except Go standard library [\#333](https://github.com/fatih/vim-go/issues/333)

- Noob question [\#329](https://github.com/fatih/vim-go/issues/329)

- Entering a colon outdents the line [\#326](https://github.com/fatih/vim-go/issues/326)

- foldmethod=syntax slowness [\#201](https://github.com/fatih/vim-go/issues/201)

**Merged pull requests:**

- Readme cleanup [\#348](https://github.com/fatih/vim-go/pull/348) ([koenwtje](https://github.com/koenwtje))

- Add ${VISUAL} to UltiSnips snippets [\#345](https://github.com/fatih/vim-go/pull/345) ([leoluz](https://github.com/leoluz))

- Return basename from BinPath function [\#343](https://github.com/fatih/vim-go/pull/343) ([kalekseev](https://github.com/kalekseev))

- doc: cleanup and update docs [\#342](https://github.com/fatih/vim-go/pull/342) ([fatih](https://github.com/fatih))

- cmd: add GoTestCompile command [\#341](https://github.com/fatih/vim-go/pull/341) ([fatih](https://github.com/fatih))

- Snippet to handle error and return [\#340](https://github.com/fatih/vim-go/pull/340) ([nowk](https://github.com/nowk))

- snippets: add a convenient testing snippet [\#339](https://github.com/fatih/vim-go/pull/339) ([fatih](https://github.com/fatih))

- oracle: add full content of referring line [\#338](https://github.com/fatih/vim-go/pull/338) ([akavel](https://github.com/akavel))

- Fix triming bracket [\#331](https://github.com/fatih/vim-go/pull/331) ([mattn](https://github.com/mattn))

- Trim needless bracket [\#330](https://github.com/fatih/vim-go/pull/330) ([mattn](https://github.com/mattn))

- feat\(snippets\) expand `errt` to `if err != nil { t.Fatal\(err\) }` [\#328](https://github.com/fatih/vim-go/pull/328) ([briantigerchow](https://github.com/briantigerchow))

- Fix oracle scope to split on whitespace [\#327](https://github.com/fatih/vim-go/pull/327) ([ghodss](https://github.com/ghodss))

- oracle: fix scope setting and add docs about usage [\#325](https://github.com/fatih/vim-go/pull/325) ([fatih](https://github.com/fatih))

- Readme cleanup [\#347](https://github.com/fatih/vim-go/pull/347) ([koenwtje](https://github.com/koenwtje))

## [v1.0.2](https://github.com/fatih/vim-go/tree/v1.0.2) (2015-02-17)

[Full Changelog](https://github.com/fatih/vim-go/compare/v1.0.1...v1.0.2)

**Fixed bugs:**

- GoFmt marks unmodified buffer as modified [\#317](https://github.com/fatih/vim-go/issues/317)

- autoindent not working [\#314](https://github.com/fatih/vim-go/issues/314)

- Issuing :GoRun results in an error [\#312](https://github.com/fatih/vim-go/issues/312)

**Closed issues:**

- Integration with gometalinter [\#320](https://github.com/fatih/vim-go/issues/320)

- tagbar is too slow to highlight the current symbol if auto\_type\_info is disabled. [\#318](https://github.com/fatih/vim-go/issues/318)

- syntax highlighting not working for me [\#316](https://github.com/fatih/vim-go/issues/316)

- Seems like the commands are not loaded [\#310](https://github.com/fatih/vim-go/issues/310)

- Docker image [\#309](https://github.com/fatih/vim-go/issues/309)

- quickfix not populated [\#307](https://github.com/fatih/vim-go/issues/307)

- GoRun with args [\#305](https://github.com/fatih/vim-go/issues/305)

- Oracle [\#250](https://github.com/fatih/vim-go/issues/250)

- Shouldn't include webapi [\#204](https://github.com/fatih/vim-go/issues/204)

- Add code generation of interface implementations [\#122](https://github.com/fatih/vim-go/issues/122)

**Merged pull requests:**

- Add a few snippets, mostly for testing [\#321](https://github.com/fatih/vim-go/pull/321) ([andrewstuart](https://github.com/andrewstuart))

- Full featured Oracle support via Quickfix list [\#319](https://github.com/fatih/vim-go/pull/319) ([fatih](https://github.com/fatih))

- indent: fix breaking behaviour with \#308, fixes \#314 [\#315](https://github.com/fatih/vim-go/pull/315) ([fatih](https://github.com/fatih))

- Enable oracle referrers command [\#311](https://github.com/fatih/vim-go/pull/311) ([akavel](https://github.com/akavel))

## [v1.0.1](https://github.com/fatih/vim-go/tree/v1.0.1) (2015-02-08)

[Full Changelog](https://github.com/fatih/vim-go/compare/v1.0...v1.0.1)

**Fixed bugs:**

- current editing file lost after ：GoRun  output error text [\#287](https://github.com/fatih/vim-go/issues/287)

- Autosave go fmt can cause vim to crash when failing sometimes [\#214](https://github.com/fatih/vim-go/issues/214)

**Closed issues:**

- Help: No syntax highlight in macvim [\#306](https://github.com/fatih/vim-go/issues/306)

- Jump back after testing [\#301](https://github.com/fatih/vim-go/issues/301)

- godef: Command not found [\#295](https://github.com/fatih/vim-go/issues/295)

- ErrCheck \(GoErrCheck\) doesn't work [\#288](https://github.com/fatih/vim-go/issues/288)

- Cannot install godef [\#285](https://github.com/fatih/vim-go/issues/285)

- Issues with Vundle install [\#283](https://github.com/fatih/vim-go/issues/283)

- Pathogen installation issue: Not an editor command: GoLint [\#282](https://github.com/fatih/vim-go/issues/282)

- GoDoc can not found correct package path when package name has extension [\#281](https://github.com/fatih/vim-go/issues/281)

- GoFmt causes neovim to crash.  [\#280](https://github.com/fatih/vim-go/issues/280)

- parseLocalPackage error: no more package files found^@godef: no declaration found for bigquery.BigqueryScope [\#277](https://github.com/fatih/vim-go/issues/277)

- Version Tags [\#274](https://github.com/fatih/vim-go/issues/274)

- Run GoTest from a remote directory.  [\#268](https://github.com/fatih/vim-go/issues/268)

**Merged pull requests:**

- Use shiftwidth\(\) instead of '&shiftwidth' [\#308](https://github.com/fatih/vim-go/pull/308) ([fd0](https://github.com/fd0))

- Goinfo typo [\#303](https://github.com/fatih/vim-go/pull/303) ([friesencr](https://github.com/friesencr))

- Update readme.md [\#297](https://github.com/fatih/vim-go/pull/297) ([nbari](https://github.com/nbari))

- Add vimproc support for vim-go. [\#296](https://github.com/fatih/vim-go/pull/296) ([jsfaint](https://github.com/jsfaint))

- fmt: check if command is different than gofmt [\#294](https://github.com/fatih/vim-go/pull/294) ([fatih](https://github.com/fatih))

- Fix errcheck, closes \#288 [\#293](https://github.com/fatih/vim-go/pull/293) ([fatih](https://github.com/fatih))

- syntax:hightlights build constraints [\#291](https://github.com/fatih/vim-go/pull/291) ([caixw](https://github.com/caixw))

- Update docs for function text objects. [\#290](https://github.com/fatih/vim-go/pull/290) ([dpetersen](https://github.com/dpetersen))

- fix GoDoc if package name differs from import path [\#289](https://github.com/fatih/vim-go/pull/289) ([ppalucki](https://github.com/ppalucki))

- \[Bugfix\]GoDoc can not found correct package path when package name has ext [\#284](https://github.com/fatih/vim-go/pull/284) ([blu3gui7ar](https://github.com/blu3gui7ar))

- Parse and add 'fatal errors' to quickfix list [\#279](https://github.com/fatih/vim-go/pull/279) ([mrnugget](https://github.com/mrnugget))

- GoImport can import "encoding/json" with `:GoImport json` [\#299](https://github.com/fatih/vim-go/pull/299) ([ppalucki](https://github.com/ppalucki))

- Add vimproc support for vim-go. [\#292](https://github.com/fatih/vim-go/pull/292) ([jsfaint](https://github.com/jsfaint))

- Fix go\#fmt\#Format for using GoImports [\#286](https://github.com/fatih/vim-go/pull/286) ([dewyze](https://github.com/dewyze))

## [v1.0](https://github.com/fatih/vim-go/tree/v1.0) (2014-12-29)

**Fixed bugs:**

- go\_bin\_path is invalid on GVIM [\#257](https://github.com/fatih/vim-go/issues/257)

- Error detected while processing function go\#fmt\#Format [\#255](https://github.com/fatih/vim-go/issues/255)

- Wrong cursor place when open file with dos line ending in Linux  [\#251](https://github.com/fatih/vim-go/issues/251)

- Cannot navigate to next error [\#247](https://github.com/fatih/vim-go/issues/247)

- Plugin appears to be loaded twice with Vim 7.4 [\#230](https://github.com/fatih/vim-go/issues/230)

- GoInstallBinaries filed to install [\#222](https://github.com/fatih/vim-go/issues/222)

- Autoformat on save: Unknown function go\#fmt\#Format [\#191](https://github.com/fatih/vim-go/issues/191)

- Append go\_bin\_path before executing any command. [\#186](https://github.com/fatih/vim-go/issues/186)

- GoVet is broken [\#169](https://github.com/fatih/vim-go/issues/169)

- "Unfixable" file [\#89](https://github.com/fatih/vim-go/issues/89)

- :GoFmt on :w mess with Vim :redo [\#40](https://github.com/fatih/vim-go/issues/40)

- error detected while processing function GoFiles [\#30](https://github.com/fatih/vim-go/issues/30)

**Closed issues:**

- GoInstallBinaries: cmd.exe can't handle single-quoted arguments [\#275](https://github.com/fatih/vim-go/issues/275)

- auto split window in macvim when type 'gd' [\#271](https://github.com/fatih/vim-go/issues/271)

- Unable to get autocomplete working [\#266](https://github.com/fatih/vim-go/issues/266)

- A syntax error in autoload/go/complete.vim [\#264](https://github.com/fatih/vim-go/issues/264)

- Is it possible to run errchecks and lint on save? [\#259](https://github.com/fatih/vim-go/issues/259)

- go\_auto\_type\_info causes screen clitches [\#254](https://github.com/fatih/vim-go/issues/254)

- GoBuild fails to build for paths that contain spaces [\#243](https://github.com/fatih/vim-go/issues/243)

- GoErrCheck returns invalid file paths [\#241](https://github.com/fatih/vim-go/issues/241)

- Fmt on save stopped working for all buffers but the last one edited [\#238](https://github.com/fatih/vim-go/issues/238)

- Escape analysis [\#231](https://github.com/fatih/vim-go/issues/231)

- Omnicomplete spawns a new buffer. [\#223](https://github.com/fatih/vim-go/issues/223)

- Snippets not consistent across neosnippets and UltiSnip [\#219](https://github.com/fatih/vim-go/issues/219)

- Can't remap <leader\>gd [\#216](https://github.com/fatih/vim-go/issues/216)

- Conceal à-la "Cute Python" [\#215](https://github.com/fatih/vim-go/issues/215)

- :GoDoc results in E117: Unknown function: go\#doc\#Open   [\#213](https://github.com/fatih/vim-go/issues/213)

- Could load vim-go plugins [\#212](https://github.com/fatih/vim-go/issues/212)

- screenshot size [\#210](https://github.com/fatih/vim-go/issues/210)

- goreturns configuration [\#208](https://github.com/fatih/vim-go/issues/208)

- Run goimports on save? [\#207](https://github.com/fatih/vim-go/issues/207)

- Multiple autocmd [\#206](https://github.com/fatih/vim-go/issues/206)

- prerename files? [\#205](https://github.com/fatih/vim-go/issues/205)

- Use dispatch or vimproc if the it's available in environment [\#202](https://github.com/fatih/vim-go/issues/202)

- Can't seem to get vim-go working :\(? [\#200](https://github.com/fatih/vim-go/issues/200)

- GoRename doesn't work for file not opened from current directory [\#199](https://github.com/fatih/vim-go/issues/199)

- Turn off autocompletion with neocomplete [\#196](https://github.com/fatih/vim-go/issues/196)

- highlight not working [\#193](https://github.com/fatih/vim-go/issues/193)

- pull request \#180 broke GoImport [\#192](https://github.com/fatih/vim-go/issues/192)

- GoDef fails to resolve named imports or dot-imports [\#190](https://github.com/fatih/vim-go/issues/190)

- Godoc command autocompletion not working [\#189](https://github.com/fatih/vim-go/issues/189)

- Add GoRename support [\#187](https://github.com/fatih/vim-go/issues/187)

- GoInstall: no install location for directory outside GOPATH [\#185](https://github.com/fatih/vim-go/issues/185)

- Error produced in go-install when $GOBIN is not set [\#184](https://github.com/fatih/vim-go/issues/184)

- vim-go + youcompleteme stops working after a while [\#179](https://github.com/fatih/vim-go/issues/179)

- goimports is not run automatically [\#178](https://github.com/fatih/vim-go/issues/178)

- vim-go: could not find 'oracle'. Run :GoInstallBinaries to fix it. [\#177](https://github.com/fatih/vim-go/issues/177)

- Thank you [\#176](https://github.com/fatih/vim-go/issues/176)

- GoImplements fails due to go\#tool\#Files command producing malformed data [\#175](https://github.com/fatih/vim-go/issues/175)

- $GOPATH not set [\#174](https://github.com/fatih/vim-go/issues/174)

- vim-go: could not find 'gofmt  [\#172](https://github.com/fatih/vim-go/issues/172)

- Add a warning if a binary is not installed [\#171](https://github.com/fatih/vim-go/issues/171)

- GoImplements is looking in my $GOPATH rather than in ~/.vim-go/ for oracle [\#170](https://github.com/fatih/vim-go/issues/170)

- stretchr/testify and :GoTest multiline issue [\#168](https://github.com/fatih/vim-go/issues/168)

- Code completion does not work [\#165](https://github.com/fatih/vim-go/issues/165)

- arrow key control characters randomly showing up on screen [\#164](https://github.com/fatih/vim-go/issues/164)

- Autocomplete from other packages in GOPATH [\#162](https://github.com/fatih/vim-go/issues/162)

- Can not detect filetype [\#161](https://github.com/fatih/vim-go/issues/161)

- Looks like the godoc command that vim-go installs is old [\#158](https://github.com/fatih/vim-go/issues/158)

- gotags: command not found [\#157](https://github.com/fatih/vim-go/issues/157)

- Go-def-tab creates new tabs [\#156](https://github.com/fatih/vim-go/issues/156)

- Disable some default syntax groups [\#155](https://github.com/fatih/vim-go/issues/155)

- go-install does not appear to work [\#154](https://github.com/fatih/vim-go/issues/154)

- GoRun command failed to open console on Windows 7 [\#153](https://github.com/fatih/vim-go/issues/153)

- With vim-go, completion with <C-n\> is very slow [\#151](https://github.com/fatih/vim-go/issues/151)

- vim-go won't let me quit [\#149](https://github.com/fatih/vim-go/issues/149)

- <Plug\> mappings not working [\#148](https://github.com/fatih/vim-go/issues/148)

- Parse errors in auto-imported packages inserted as content [\#147](https://github.com/fatih/vim-go/issues/147)

- vim-go's syntactic highlighting makes vim super slow when dealing with long lines [\#145](https://github.com/fatih/vim-go/issues/145)

- vim freezes for a couple of seconds when saving go files [\#144](https://github.com/fatih/vim-go/issues/144)

- install on chromebook chroot [\#143](https://github.com/fatih/vim-go/issues/143)

- support for go templates [\#141](https://github.com/fatih/vim-go/issues/141)

- vim-go maps the K key to doc lookup [\#140](https://github.com/fatih/vim-go/issues/140)

- vim-go: gocode not found... errors [\#139](https://github.com/fatih/vim-go/issues/139)

- gvm integration [\#137](https://github.com/fatih/vim-go/issues/137)

- vim prints contents of entire file when saving [\#136](https://github.com/fatih/vim-go/issues/136)

- Vim Go slow to save after run goxc [\#134](https://github.com/fatih/vim-go/issues/134)

- Auto completion with custom bin path stops working [\#133](https://github.com/fatih/vim-go/issues/133)

- Comment out unused variables and imports [\#131](https://github.com/fatih/vim-go/issues/131)

- :GoFmt on save mess up with last modified position [\#130](https://github.com/fatih/vim-go/issues/130)

- Not an editor command: GoDoc [\#129](https://github.com/fatih/vim-go/issues/129)

- Snippets not working [\#127](https://github.com/fatih/vim-go/issues/127)

- Add a function returning details of the identifier under the cursor [\#125](https://github.com/fatih/vim-go/issues/125)

- Autoimporting seems to be broken since 8d6cbe0 [\#124](https://github.com/fatih/vim-go/issues/124)

- vim-go produces rendering artifacts in terminal vim [\#123](https://github.com/fatih/vim-go/issues/123)

- Output problems after GoBuild [\#120](https://github.com/fatih/vim-go/issues/120)

- No output for GoRun  [\#117](https://github.com/fatih/vim-go/issues/117)

- :GoDef does not support pointers [\#110](https://github.com/fatih/vim-go/issues/110)

- Getting a bunch of errors on starting vim [\#109](https://github.com/fatih/vim-go/issues/109)

- Quickfix window opening beneath TagBar [\#108](https://github.com/fatih/vim-go/issues/108)

- Improved Oracle integration [\#107](https://github.com/fatih/vim-go/issues/107)

- Panic opens incorrect file [\#106](https://github.com/fatih/vim-go/issues/106)

- It would be nice for GoTest to take a package/path param. [\#105](https://github.com/fatih/vim-go/issues/105)

- Mapping for next error in Quickfix List [\#101](https://github.com/fatih/vim-go/issues/101)

- Static analysis of godoc [\#99](https://github.com/fatih/vim-go/issues/99)

- Incorrect opening of file after GoRun [\#98](https://github.com/fatih/vim-go/issues/98)

- Not an editor command on Godef, Gobuild etc, formatting working [\#96](https://github.com/fatih/vim-go/issues/96)

- Remove required dep on mercurial [\#95](https://github.com/fatih/vim-go/issues/95)

- Snippets consistency [\#94](https://github.com/fatih/vim-go/issues/94)

- Getting Vim-go running on Windows [\#93](https://github.com/fatih/vim-go/issues/93)

- Rename plugin/tagbar.vim [\#91](https://github.com/fatih/vim-go/issues/91)

- Error downloading/installing all necessary go binaries [\#90](https://github.com/fatih/vim-go/issues/90)

- expose GoDocBrowser as a mapping [\#88](https://github.com/fatih/vim-go/issues/88)

- vim.go: $GOPATH is not set [\#86](https://github.com/fatih/vim-go/issues/86)

- go executable not found [\#85](https://github.com/fatih/vim-go/issues/85)

- Error installing godef [\#84](https://github.com/fatih/vim-go/issues/84)

- Additional "Tab" character in filepath after GoTest [\#83](https://github.com/fatih/vim-go/issues/83)

- Install via Vundle not working [\#82](https://github.com/fatih/vim-go/issues/82)

- go\#tool\#ShowErrors shows incorrect filename on :GoTest [\#81](https://github.com/fatih/vim-go/issues/81)

- vim.go: hg \(mercurial\) executable not found. [\#79](https://github.com/fatih/vim-go/issues/79)

- I found error vim.go: hg \(mercurial\) executable not found. [\#77](https://github.com/fatih/vim-go/issues/77)

- Not highlighting functions. [\#76](https://github.com/fatih/vim-go/issues/76)

- Saving file removes import block [\#73](https://github.com/fatih/vim-go/issues/73)

- Function syntax highlighting slow [\#72](https://github.com/fatih/vim-go/issues/72)

- Some weird characters are printed onto the screen [\#71](https://github.com/fatih/vim-go/issues/71)

- Not an editor command: GoFmt [\#69](https://github.com/fatih/vim-go/issues/69)

- gocode + omnifunction integration broken. [\#67](https://github.com/fatih/vim-go/issues/67)

- Installing under vundle tries, fails to write to privileged $GOROOT folder [\#66](https://github.com/fatih/vim-go/issues/66)

- Need to install godoc manually? [\#65](https://github.com/fatih/vim-go/issues/65)

- Wrong stat [\#63](https://github.com/fatih/vim-go/issues/63)

- E117: Unknown function : go\#complete\#Complete [\#61](https://github.com/fatih/vim-go/issues/61)

- Add GoTags support [\#59](https://github.com/fatih/vim-go/issues/59)

- GoDoc opens browser [\#58](https://github.com/fatih/vim-go/issues/58)

- Don't disable GoUpdateBinaries with g:go\_disable\_autoinstall = 1 [\#57](https://github.com/fatih/vim-go/issues/57)

- Error installing goimports, oracle and errcheck [\#56](https://github.com/fatih/vim-go/issues/56)

- Check a trailing path slash [\#53](https://github.com/fatih/vim-go/issues/53)

- Cannot autocomplete on assigment [\#52](https://github.com/fatih/vim-go/issues/52)

- GoDoc should be open in split,vertical or new tab [\#51](https://github.com/fatih/vim-go/issues/51)

- Add <Plug\>\(go-...\) mappings to let users create easy mappings [\#46](https://github.com/fatih/vim-go/issues/46)

- GoDoc not working with nested packages [\#45](https://github.com/fatih/vim-go/issues/45)

- Removes imports on :w. [\#43](https://github.com/fatih/vim-go/issues/43)

- gosnippet.vim breaks supertab [\#42](https://github.com/fatih/vim-go/issues/42)

- Fix :make and :GoBuild [\#41](https://github.com/fatih/vim-go/issues/41)

- Support for `go vet` [\#39](https://github.com/fatih/vim-go/issues/39)

- Implement vim-dispatch for builds,tests and runs [\#38](https://github.com/fatih/vim-go/issues/38)

- installer doesn't report GOPATH issue [\#37](https://github.com/fatih/vim-go/issues/37)

- Add g:go\_fmt\_options to pass command option [\#36](https://github.com/fatih/vim-go/issues/36)

- Add g:go\_fmt\_failsilently option [\#35](https://github.com/fatih/vim-go/issues/35)

- GoErrCheck only opens a new window the first time it is run [\#34](https://github.com/fatih/vim-go/issues/34)

- Snippet support for neosnippet [\#31](https://github.com/fatih/vim-go/issues/31)

- Consider using $XDG\_CONFIG\_HOME instead of ~/.vim-go [\#28](https://github.com/fatih/vim-go/issues/28)

- E154: Duplicate tag ":GoFmt" in file github-fatih-vim-go/doc/vim-go.txt [\#27](https://github.com/fatih/vim-go/issues/27)

- Warn when mercurial isn't installed [\#26](https://github.com/fatih/vim-go/issues/26)

- gofmt integration is not working [\#25](https://github.com/fatih/vim-go/issues/25)

- Error when running Fmt: [\#24](https://github.com/fatih/vim-go/issues/24)

- Change and add `Go` prefix to missing commands. [\#23](https://github.com/fatih/vim-go/issues/23)

- nicer build visualization [\#22](https://github.com/fatih/vim-go/issues/22)

- Add share to play.golang.org [\#20](https://github.com/fatih/vim-go/issues/20)

- Highlight method function [\#19](https://github.com/fatih/vim-go/issues/19)

- Implement errcheck [\#18](https://github.com/fatih/vim-go/issues/18)

- :Gorun should accept file arguments [\#17](https://github.com/fatih/vim-go/issues/17)

- Implement :Gorun to quickly run a command [\#16](https://github.com/fatih/vim-go/issues/16)

- Show :Lint in Quickfix window, the current way seems to be inefficent. [\#15](https://github.com/fatih/vim-go/issues/15)

- Change :Import which imports the package under the cursor [\#14](https://github.com/fatih/vim-go/issues/14)

- Deleted [\#13](https://github.com/fatih/vim-go/issues/13)

- Add doc directory with proper vim-docs. [\#12](https://github.com/fatih/vim-go/issues/12)

- Add option to disabe auto\_install [\#11](https://github.com/fatih/vim-go/issues/11)

- Implement :Gotest  [\#10](https://github.com/fatih/vim-go/issues/10)

- Implement :Gobuild that doesn't produce any binary, but outputs error if any [\#9](https://github.com/fatih/vim-go/issues/9)

- Rename global variable to g:vimgo\_... [\#8](https://github.com/fatih/vim-go/issues/8)

- Change binary path to ~/.vim-go [\#7](https://github.com/fatih/vim-go/issues/7)

- Add goimports feature [\#6](https://github.com/fatih/vim-go/issues/6)

- Auto go fmt on save [\#5](https://github.com/fatih/vim-go/issues/5)

- Add well known snippets and snippet support [\#4](https://github.com/fatih/vim-go/issues/4)

- go-oracle integration [\#3](https://github.com/fatih/vim-go/issues/3)

- Godef integration [\#2](https://github.com/fatih/vim-go/issues/2)

- Autocomplete feature [\#1](https://github.com/fatih/vim-go/issues/1)

**Merged pull requests:**

- Fix \#275: Unset and reset shellslash if on Windows [\#276](https://github.com/fatih/vim-go/pull/276) ([Solumin](https://github.com/Solumin))

- Oracle callees mode implementation [\#273](https://github.com/fatih/vim-go/pull/273) ([fatih](https://github.com/fatih))

- Custom text objects [\#272](https://github.com/fatih/vim-go/pull/272) ([lucapette](https://github.com/lucapette))

- Only show tests passed if test cmd was successful [\#270](https://github.com/fatih/vim-go/pull/270) ([mrnugget](https://github.com/mrnugget))

- fixed unnecessary buffer creation [\#269](https://github.com/fatih/vim-go/pull/269) ([lynnard](https://github.com/lynnard))

- Make GoRename work under zsh [\#265](https://github.com/fatih/vim-go/pull/265) ([junkblocker](https://github.com/junkblocker))

- rename.vim: follow symlinks so gorename knows it [\#263](https://github.com/fatih/vim-go/pull/263) ([fatih](https://github.com/fatih))

- fmt.vim: make wundo action changable [\#262](https://github.com/fatih/vim-go/pull/262) ([fatih](https://github.com/fatih))

- Set 'makeprg' variable as 'make' when Makefile exists [\#261](https://github.com/fatih/vim-go/pull/261) ([yunkai](https://github.com/yunkai))

- Include cgo files in go\#tool\#Files listings [\#260](https://github.com/fatih/vim-go/pull/260) ([mirtchovski](https://github.com/mirtchovski))

- Add more of the io Interfaces to syntax. [\#258](https://github.com/fatih/vim-go/pull/258) ([omeid](https://github.com/omeid))

- This should fix fatih/vim-go\#251 \(GoDef and non unix line endings\). [\#253](https://github.com/fatih/vim-go/pull/253) ([alexaandru](https://github.com/alexaandru))

- Support :GoDoc with only package name [\#249](https://github.com/fatih/vim-go/pull/249) ([bernerdschaefer](https://github.com/bernerdschaefer))

- Fix highlight type, add highlighting of format strings [\#246](https://github.com/fatih/vim-go/pull/246) ([millere](https://github.com/millere))

- Ultisnips: fix automatic parentheses insertion with function types [\#245](https://github.com/fatih/vim-go/pull/245) ([gcmt](https://github.com/gcmt))

- Fix GoBuild for paths with spaces \(fatih/vim-go\#243\) [\#244](https://github.com/fatih/vim-go/pull/244) ([alexaandru](https://github.com/alexaandru))

- Fixes https://github.com/fatih/vim-go/issues/241 [\#242](https://github.com/fatih/vim-go/pull/242) ([alexaandru](https://github.com/alexaandru))

- More cleanup related to issue https://github.com/fatih/vim-go/issues/222 [\#240](https://github.com/fatih/vim-go/pull/240) ([alexaandru](https://github.com/alexaandru))

- Move autocommands to plugin/go.vim. [\#239](https://github.com/fatih/vim-go/pull/239) ([gcmt](https://github.com/gcmt))

- Added support for passing build flags to GoBuild [\#237](https://github.com/fatih/vim-go/pull/237) ([alexaandru](https://github.com/alexaandru))

- Fixes the issue with installing binaries on Windows [\#236](https://github.com/fatih/vim-go/pull/236) ([alexaandru](https://github.com/alexaandru))

- Open GoDef window silently [\#235](https://github.com/fatih/vim-go/pull/235) ([gcmt](https://github.com/gcmt))

- Open GoDoc window silently [\#234](https://github.com/fatih/vim-go/pull/234) ([gcmt](https://github.com/gcmt))

- Group autocommands / Minor refactoring [\#232](https://github.com/fatih/vim-go/pull/232) ([gcmt](https://github.com/gcmt))

- Ultisnips: automatic parentheses insertion with multiple return values [\#229](https://github.com/fatih/vim-go/pull/229) ([gcmt](https://github.com/gcmt))

- Stay silent if type info isn't found for the word under cursor [\#228](https://github.com/fatih/vim-go/pull/228) ([gcmt](https://github.com/gcmt))

- update README to help users enable syntax highlight for functions, methods & structs [\#227](https://github.com/fatih/vim-go/pull/227) ([michael-go](https://github.com/michael-go))

- Update paths for go tools [\#225](https://github.com/fatih/vim-go/pull/225) ([freeformz](https://github.com/freeformz))

- Fix GoErrCheck and support passing an optional package [\#224](https://github.com/fatih/vim-go/pull/224) ([tchajed](https://github.com/tchajed))

- Unify snippets for UltiSnips and neosnippets [\#220](https://github.com/fatih/vim-go/pull/220) ([jonhoo](https://github.com/jonhoo))

- Removing annoying trailing whitespace from documentation [\#218](https://github.com/fatih/vim-go/pull/218) ([glauco](https://github.com/glauco))

- Update vim-go.txt: 'goimportes' -\> 'goimports' [\#209](https://github.com/fatih/vim-go/pull/209) ([weberc2](https://github.com/weberc2))

- Implement GoRename \(closes \#187\) [\#198](https://github.com/fatih/vim-go/pull/198) ([fatih](https://github.com/fatih))

- doc: replace godoc to  g:go\_doc\_command and g:go\_doc\_options [\#197](https://github.com/fatih/vim-go/pull/197) ([matsuu](https://github.com/matsuu))

- Fix an error in complete.vim [\#194](https://github.com/fatih/vim-go/pull/194) ([jeremyschlatter](https://github.com/jeremyschlatter))

- install: add GOPATH or GOBIN to the list of executables [\#188](https://github.com/fatih/vim-go/pull/188) ([fatih](https://github.com/fatih))

- Load snippets with neosnippet.vim dynamically. [\#183](https://github.com/fatih/vim-go/pull/183) ([mitsuse](https://github.com/mitsuse))

- vim-go: move functions to autoload folder for lazy loading [\#180](https://github.com/fatih/vim-go/pull/180) ([fatih](https://github.com/fatih))

- vim-go: several cleanups and behaviour changes [\#166](https://github.com/fatih/vim-go/pull/166) ([fatih](https://github.com/fatih))

- Fix godef tab [\#163](https://github.com/fatih/vim-go/pull/163) ([fatih](https://github.com/fatih))

- Make auto jump to error optional [\#160](https://github.com/fatih/vim-go/pull/160) ([nowk](https://github.com/nowk))

- make option vars global [\#159](https://github.com/fatih/vim-go/pull/159) ([Xuyuanp](https://github.com/Xuyuanp))

- mappings: no need to use hasmapto, fixes \#148 [\#152](https://github.com/fatih/vim-go/pull/152) ([fatih](https://github.com/fatih))

- Improved gofmt [\#150](https://github.com/fatih/vim-go/pull/150) ([fatih](https://github.com/fatih))

- add minimal addon-info.json file [\#146](https://github.com/fatih/vim-go/pull/146) ([willnorris](https://github.com/willnorris))

- Proposed fix for fatih/vim-go\#93 [\#142](https://github.com/fatih/vim-go/pull/142) ([fawick](https://github.com/fawick))

- Completion doesn't work when &encoding isn't utf-8 AND &fileformat is dos [\#138](https://github.com/fatih/vim-go/pull/138) ([opennota](https://github.com/opennota))

- Support autocompletion of path in GoImportAs [\#135](https://github.com/fatih/vim-go/pull/135) ([tuxychandru](https://github.com/tuxychandru))

- Change neosnippets filename [\#132](https://github.com/fatih/vim-go/pull/132) ([volkhin](https://github.com/volkhin))

- fix spelling error in readme [\#128](https://github.com/fatih/vim-go/pull/128) ([dietsche](https://github.com/dietsche))

- Add function returning details about identifier under cursor in Go [\#126](https://github.com/fatih/vim-go/pull/126) ([tiziano88](https://github.com/tiziano88))

- Make vim-go a little more friendly to other plugins and non-go environments [\#121](https://github.com/fatih/vim-go/pull/121) ([jmcantrell](https://github.com/jmcantrell))

- Added ff snippet for neosnippet [\#119](https://github.com/fatih/vim-go/pull/119) ([schickling](https://github.com/schickling))

- Oracle integration improvements [\#116](https://github.com/fatih/vim-go/pull/116) ([fatih](https://github.com/fatih))

- Don't shellescape our oracle scope file; enables multiple packages in scope [\#115](https://github.com/fatih/vim-go/pull/115) ([seantalts](https://github.com/seantalts))

- default map gd to :GoDef [\#114](https://github.com/fatih/vim-go/pull/114) ([hoffoo](https://github.com/hoffoo))

- Minor typo/language fix. [\#113](https://github.com/fatih/vim-go/pull/113) ([sinan](https://github.com/sinan))

- Capture multi-line error output [\#112](https://github.com/fatih/vim-go/pull/112) ([dsymonds](https://github.com/dsymonds))

- Improve `for` loop snippet; add separate `for condition` snippet [\#104](https://github.com/fatih/vim-go/pull/104) ([opennota](https://github.com/opennota))

- Error return snippets with two and three values [\#103](https://github.com/fatih/vim-go/pull/103) ([opennota](https://github.com/opennota))

- Fix copy-paste error in the docs; spellcheck README.md [\#92](https://github.com/fatih/vim-go/pull/92) ([opennota](https://github.com/opennota))

- Update doc according to last change on GoInfo behavior [\#87](https://github.com/fatih/vim-go/pull/87) ([tbruyelle](https://github.com/tbruyelle))

- Note dependency on mercurial [\#80](https://github.com/fatih/vim-go/pull/80) ([rgbkrk](https://github.com/rgbkrk))

- UltiSnips: Additional jump points for the 'package' snippet. [\#78](https://github.com/fatih/vim-go/pull/78) ([bmatsuo](https://github.com/bmatsuo))

- UltiSnips: remove duplicate snippet "forr" [\#75](https://github.com/fatih/vim-go/pull/75) ([bmatsuo](https://github.com/bmatsuo))

- Add Test snippet [\#74](https://github.com/fatih/vim-go/pull/74) ([bcarrell](https://github.com/bcarrell))

- Fixing tagbar support for ceocoder [\#70](https://github.com/fatih/vim-go/pull/70) ([smeggingsmegger](https://github.com/smeggingsmegger))

- Fixed README [\#68](https://github.com/fatih/vim-go/pull/68) ([mattikus](https://github.com/mattikus))

- Close quickfix window on successful fmt [\#64](https://github.com/fatih/vim-go/pull/64) ([zenazn](https://github.com/zenazn))

- Fix some typos in README.md [\#62](https://github.com/fatih/vim-go/pull/62) ([yoshikischmitz](https://github.com/yoshikischmitz))

- Disable expandtab [\#55](https://github.com/fatih/vim-go/pull/55) ([nnutter](https://github.com/nnutter))

- An universal way checking executable existence [\#54](https://github.com/fatih/vim-go/pull/54) ([bohrshaw](https://github.com/bohrshaw))

- Fix case for GoDoc mapping [\#50](https://github.com/fatih/vim-go/pull/50) ([lucapette](https://github.com/lucapette))

- improve syntax highlighting for godoc [\#48](https://github.com/fatih/vim-go/pull/48) ([fjl](https://github.com/fjl))

- Added GoInstall command [\#47](https://github.com/fatih/vim-go/pull/47) ([riobard](https://github.com/riobard))

- improve GoOracle automatic scope handling [\#44](https://github.com/fatih/vim-go/pull/44) ([foubarre](https://github.com/foubarre))

- Fix typo [\#33](https://github.com/fatih/vim-go/pull/33) ([lucapette](https://github.com/lucapette))

- Don't overwrite `g:UltiSnipsSnippetDirectories` [\#32](https://github.com/fatih/vim-go/pull/32) ([lucapette](https://github.com/lucapette))

- Update README.md [\#29](https://github.com/fatih/vim-go/pull/29) ([sethgrid](https://github.com/sethgrid))

- Changed README.md to recursive YCM clone [\#21](https://github.com/fatih/vim-go/pull/21) ([beefsack](https://github.com/beefsack))

- use new import paths for Go sub-repositories [\#226](https://github.com/fatih/vim-go/pull/226) ([mmlb](https://github.com/mmlb))

- Added a few links [\#203](https://github.com/fatih/vim-go/pull/203) ([xarg](https://github.com/xarg))

- Update README.md [\#195](https://github.com/fatih/vim-go/pull/195) ([dlintw](https://github.com/dlintw))

- Load snippets with neosnippet.vim dynamically for .go file opened in new window. [\#181](https://github.com/fatih/vim-go/pull/181) ([mitsuse](https://github.com/mitsuse))

- fix tool.vim::go\#tool\#BinExists\(\) [\#173](https://github.com/fatih/vim-go/pull/173) ([alvan](https://github.com/alvan))

- Add benchmark command for running benchmarks [\#167](https://github.com/fatih/vim-go/pull/167) ([lukebergen](https://github.com/lukebergen))

- check import before :GoImport [\#118](https://github.com/fatih/vim-go/pull/118) ([hoffoo](https://github.com/hoffoo))

- Remap shift-k to GoDoc instead of man [\#111](https://github.com/fatih/vim-go/pull/111) ([hoffoo](https://github.com/hoffoo))

- Support for lazy loading UltiSnips [\#102](https://github.com/fatih/vim-go/pull/102) ([opennota](https://github.com/opennota))

- Introduce go\_fmt\_quickfix. [\#100](https://github.com/fatih/vim-go/pull/100) ([omeid](https://github.com/omeid))

- Basic CI configuration [\#97](https://github.com/fatih/vim-go/pull/97) ([txomon](https://github.com/txomon))

- Adding support for TabBar with Gotags [\#60](https://github.com/fatih/vim-go/pull/60) ([ceocoder](https://github.com/ceocoder))

- fix E715 \(dictionary required\) when :GoDoc is run outside a package [\#49](https://github.com/fatih/vim-go/pull/49) ([fjl](https://github.com/fjl))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*