This list was created with:

+ curl https://api.github.com/search/issues?q="repo%3Ajson-c%2Fjson-c+closed%3A>2017-12-07+created%3A<2020-04-17&sort=created&order=asc&per_page=400&page=1" > issues1.out

+ curl https://api.github.com/search/issues?q="repo%3Ajson-c%2Fjson-c+closed%3A>2017-12-07+created%3A<2020-04-17&sort=created&order=asc&per_page=400&page=2" > issues2.out

+ curl https://api.github.com/search/issues?q="repo%3Ajson-c%2Fjson-c+closed%3A>2017-12-07+created%3A<2020-04-17&sort=created&order=asc&per_page=400&page=3" > issues3.out

+ jq -r '.items[] | "[" + .title + "](" + .url + ")" | tostring' issues?.out > issues.md

+ \#... manual editing ...

----



Issues and Pull Requests closed for the 0.14 release (since commit d582d3a(2017-12-07) to a911439(2020-04-17))



[Add utf-8 validation when parsing strings.](https://api.github.com/repos/json-c/json-c/issues/122)  
[json_object_from_file cannot accept max_depth](https://api.github.com/repos/json-c/json-c/issues/139)  
[RFE / enhancement for full 64-bit signed/unsigned support](https://api.github.com/repos/json-c/json-c/issues/143)  
[Please introduce soname bump if API changed](https://api.github.com/repos/json-c/json-c/issues/147)  
[Need a way to specify nesting depth when opening JSON file](https://api.github.com/repos/json-c/json-c/issues/166)  
[There is no json_object_new_null()](https://api.github.com/repos/json-c/json-c/issues/226)  
[new release ?](https://api.github.com/repos/json-c/json-c/issues/314)  
[Please extend api json_object_get_uint64](https://api.github.com/repos/json-c/json-c/issues/326)  
[Switch json-c builds to use CMake](https://api.github.com/repos/json-c/json-c/issues/334)  
[Makefile: Add ACLOCAL_AMFLAGS](https://api.github.com/repos/json-c/json-c/issues/386)  
[doc: Use other doxygen feature to specify mainpage](https://api.github.com/repos/json-c/json-c/issues/387)  
[json_object: Add size_t json_object_sizeof()](https://api.github.com/repos/json-c/json-c/issues/388)  
[json_object: Avoid double free (and thus a segfault) when ref_count gets < 0](https://api.github.com/repos/json-c/json-c/issues/389)  
[json_object: Add const size_t json_c_object_sizeof()](https://api.github.com/repos/json-c/json-c/issues/390)  
[Fix non-GNUC define for JSON_C_CONST_FUNCTION](https://api.github.com/repos/json-c/json-c/issues/391)  
[json_object: Avoid invalid free (and thus a segfault) when ref_count gets < 0](https://api.github.com/repos/json-c/json-c/issues/392)  
[json_object_private: Use unsigned 32-bit integer type for refcount](https://api.github.com/repos/json-c/json-c/issues/393)  
[Problem serializing double](https://api.github.com/repos/json-c/json-c/issues/394)  
[Key gets modified if it contains "\"](https://api.github.com/repos/json-c/json-c/issues/395)  
[Build failure with no threads uClibc toolchain](https://api.github.com/repos/json-c/json-c/issues/396)  
[update json object with key.](https://api.github.com/repos/json-c/json-c/issues/397)  
[Build failed.](https://api.github.com/repos/json-c/json-c/issues/398)  
[Avoid uninitialized variable warnings](https://api.github.com/repos/json-c/json-c/issues/399)  
[How to generate static lib (.a)](https://api.github.com/repos/json-c/json-c/issues/400)  
[Warnings with Valgrind](https://api.github.com/repos/json-c/json-c/issues/401)  
[Add fuzzers from OSS-Fuzz](https://api.github.com/repos/json-c/json-c/issues/402)  
[Segmentation fault when double quotes is used ](https://api.github.com/repos/json-c/json-c/issues/403)  
[valgrind: memory leak](https://api.github.com/repos/json-c/json-c/issues/404)  
[Missing API to determine an object is empty](https://api.github.com/repos/json-c/json-c/issues/405)  
[Undefine NDEBUG for tests](https://api.github.com/repos/json-c/json-c/issues/406)  
[json_tokener_parse is crash ](https://api.github.com/repos/json-c/json-c/issues/407)  
[bug in array_list_del_idx when array_list_length()==1](https://api.github.com/repos/json-c/json-c/issues/408)  
[Fixed typos](https://api.github.com/repos/json-c/json-c/issues/410)  
[Crash- signal SIGSEGV, Segmentation fault. ../sysdeps/x86_64/strlen.S: No such file or directory.](https://api.github.com/repos/json-c/json-c/issues/411)  
[json_type changes during inter process communication.](https://api.github.com/repos/json-c/json-c/issues/412)  
[how to read object of type `json_object *` in c++](https://api.github.com/repos/json-c/json-c/issues/413)  
[[Question] How JSON-c stores the serialized data in memory?](https://api.github.com/repos/json-c/json-c/issues/414)  
[Resolve windows name conflict](https://api.github.com/repos/json-c/json-c/issues/415)  
[segmentation fault  in json_tokener_parse](https://api.github.com/repos/json-c/json-c/issues/416)  
[json_tokener_parse  json_object_object_get_ex with string value which is json string](https://api.github.com/repos/json-c/json-c/issues/417)  
[json_object_from_* return value documented incorrectly](https://api.github.com/repos/json-c/json-c/issues/418)  
[Suggestion: document (and define) that json_object_put() accepts NULL pointer to object](https://api.github.com/repos/json-c/json-c/issues/419)  
[arraylist: Fixed names of parameters for callback function](https://api.github.com/repos/json-c/json-c/issues/420)  
[install json_object_iterator.h header file](https://api.github.com/repos/json-c/json-c/issues/421)  
[json_object_get_double() does not set errno when there is no valid conversion](https://api.github.com/repos/json-c/json-c/issues/422)  
[memory leak](https://api.github.com/repos/json-c/json-c/issues/423)  
[Parse string contains "\" or "/" errors](https://api.github.com/repos/json-c/json-c/issues/424)  
[what this is?](https://api.github.com/repos/json-c/json-c/issues/425)  
[__deprecated not supported on clang.](https://api.github.com/repos/json-c/json-c/issues/426)  
[CMake: builds involving this target will not be correct](https://api.github.com/repos/json-c/json-c/issues/427)  
[json_object_object_del() and Segmentation fault](https://api.github.com/repos/json-c/json-c/issues/430)  
[cmake: Bump required version](https://api.github.com/repos/json-c/json-c/issues/431)  
[The real CMake support.](https://api.github.com/repos/json-c/json-c/issues/432)  
[The real CMake support.](https://api.github.com/repos/json-c/json-c/issues/433)  
[The real CMake support](https://api.github.com/repos/json-c/json-c/issues/434)  
[json_object_object_del() segmentation fault](https://api.github.com/repos/json-c/json-c/issues/435)  
[Improve pkgconfig setting](https://api.github.com/repos/json-c/json-c/issues/436)  
[Bad link in README.md](https://api.github.com/repos/json-c/json-c/issues/437)  
[Bad link in README.html](https://api.github.com/repos/json-c/json-c/issues/438)  
[reserved identifier violation](https://api.github.com/repos/json-c/json-c/issues/439)  
[Use of angle brackets around file names for include statements](https://api.github.com/repos/json-c/json-c/issues/440)  
[fix c flag loss during cmake building](https://api.github.com/repos/json-c/json-c/issues/441)  
[error  in configure file](https://api.github.com/repos/json-c/json-c/issues/442)  
[remove pretty spaces when using pretty tabs](https://api.github.com/repos/json-c/json-c/issues/443)  
[Document refcount of json_tokener_parse_ex return](https://api.github.com/repos/json-c/json-c/issues/444)  
[Add missing "make check" target to cmake config](https://api.github.com/repos/json-c/json-c/issues/445)  
[Forward slashes get escaped](https://api.github.com/repos/json-c/json-c/issues/446)  
[Buffer overflow in json-c](https://api.github.com/repos/json-c/json-c/issues/448)  
[Need of json_type_int64 returned by json_object_get_type()](https://api.github.com/repos/json-c/json-c/issues/449)  
[Allow use json-c cmake as subproject](https://api.github.com/repos/json-c/json-c/issues/450)  
[Update README.md](https://api.github.com/repos/json-c/json-c/issues/452)  
[Fixed misalignment in JSON string due to space after \n being printed...](https://api.github.com/repos/json-c/json-c/issues/453)  
[json_object_private: save 8 bytes in struct json_object in 64-bit arc…](https://api.github.com/repos/json-c/json-c/issues/454)  
[index.html:fix dead link](https://api.github.com/repos/json-c/json-c/issues/455)  
[STYLE.txt:remove executable permissions](https://api.github.com/repos/json-c/json-c/issues/456)  
[.gitignore:add build directory](https://api.github.com/repos/json-c/json-c/issues/457)  
[README.md:fix dead "file.html" link](https://api.github.com/repos/json-c/json-c/issues/458)  
[README.html:fix link to Doxygen docs, remove WIN32 link](https://api.github.com/repos/json-c/json-c/issues/459)  
[No docs for json_object_new_string_len()](https://api.github.com/repos/json-c/json-c/issues/460)  
[json_object.c:set errno in json_object_get_double()](https://api.github.com/repos/json-c/json-c/issues/461)  
[json_object.h:document json_object_new_string_len()](https://api.github.com/repos/json-c/json-c/issues/462)  
[please check newlocale api first argument valuse.](https://api.github.com/repos/json-c/json-c/issues/463)  
[CMakeLists.txt doesn't contain json_object_iterator.h which json.h includes](https://api.github.com/repos/json-c/json-c/issues/465)  
[configure:3610: error: C compiler cannot create executables](https://api.github.com/repos/json-c/json-c/issues/466)  
[Fix compiler warnings](https://api.github.com/repos/json-c/json-c/issues/467)  
[Fix compiler warnings](https://api.github.com/repos/json-c/json-c/issues/468)  
[Build under alpine with pecl install & docker-php-ext-enable?](https://api.github.com/repos/json-c/json-c/issues/469)  
[cfuhash_foreach_remove doesn't upate cfuhash_num_entries](https://api.github.com/repos/json-c/json-c/issues/470)  
[Segmentation fault in json_object_iter_begin](https://api.github.com/repos/json-c/json-c/issues/472)  
[Convert ChangeLog to valid UTF-8 encoding.](https://api.github.com/repos/json-c/json-c/issues/473)  
[Installation directories empty with CMake in pkg-config.](https://api.github.com/repos/json-c/json-c/issues/474)  
[improvement proposal for json_object_object_foreach](https://api.github.com/repos/json-c/json-c/issues/475)  
[Hang/Crash with large strings](https://api.github.com/repos/json-c/json-c/issues/477)  
[json_object_get_string_len returns 0 when value is number](https://api.github.com/repos/json-c/json-c/issues/478)  
[I want to use it in iOS or Android but I can't compile](https://api.github.com/repos/json-c/json-c/issues/479)  
[json-c-0.12.1  failed making from source code](https://api.github.com/repos/json-c/json-c/issues/480)  
[ error while loading shared libraries: libjson-c.so.4](https://api.github.com/repos/json-c/json-c/issues/481)  
[Error "double free or corruption" after free()](https://api.github.com/repos/json-c/json-c/issues/482)  
[compatible with rarely-used Chinese characters in GBK charset](https://api.github.com/repos/json-c/json-c/issues/483)  
[Install CMake module files](https://api.github.com/repos/json-c/json-c/issues/485)  
[In the case of negative double value, it is formatted without including ".0"](https://api.github.com/repos/json-c/json-c/issues/486)  
[Some APIs are not exported when built as shared lib on Win32](https://api.github.com/repos/json-c/json-c/issues/488)  
[Don't use -Werror by default](https://api.github.com/repos/json-c/json-c/issues/489)  
[do not compile with -Werror by default](https://api.github.com/repos/json-c/json-c/issues/490)  
[build: add option --disable-werror to configure](https://api.github.com/repos/json-c/json-c/issues/491)  
[lack some quick usage in readme](https://api.github.com/repos/json-c/json-c/issues/492)  
[Code generator?](https://api.github.com/repos/json-c/json-c/issues/494)  
[README.md:fix 2 typos](https://api.github.com/repos/json-c/json-c/issues/495)  
[json_pointer.h:suggest minor grammar improvement for pointer doc](https://api.github.com/repos/json-c/json-c/issues/496)  
[add common header for all tests](https://api.github.com/repos/json-c/json-c/issues/497)  
[double_serializer_test fails (with valgrind)](https://api.github.com/repos/json-c/json-c/issues/498)  
[.travis.yml:test on more recent clang and gcc versions](https://api.github.com/repos/json-c/json-c/issues/499)  
[test/Makefile.am:add missing deps for test1 and test2](https://api.github.com/repos/json-c/json-c/issues/500)  
[undefine NDEBUG for tests](https://api.github.com/repos/json-c/json-c/issues/501)  
[configure error](https://api.github.com/repos/json-c/json-c/issues/502)  
[json-c retuns OK when Invalid json string is passed](https://api.github.com/repos/json-c/json-c/issues/503)  
[json_object_put coredump](https://api.github.com/repos/json-c/json-c/issues/504)  
[Add vcpkg installation instructions](https://api.github.com/repos/json-c/json-c/issues/505)  
[Cannot parse more than one object](https://api.github.com/repos/json-c/json-c/issues/506)  
[Sometimes a double value is not serialized ](https://api.github.com/repos/json-c/json-c/issues/509)  
[Bump so-name and improve CMake](https://api.github.com/repos/json-c/json-c/issues/510)  
[Reduce lines for better optimization](https://api.github.com/repos/json-c/json-c/issues/511)  
[Properly append to CMAKE_C_FLAGS string](https://api.github.com/repos/json-c/json-c/issues/512)  
[What does `userdata` means?And what is the case we can use it?](https://api.github.com/repos/json-c/json-c/issues/513)  
[Json c 0.13](https://api.github.com/repos/json-c/json-c/issues/514)  
[Mies suomesta fixes segfaults and logic errors](https://api.github.com/repos/json-c/json-c/issues/515)  
[Lja slight mods](https://api.github.com/repos/json-c/json-c/issues/516)  
[Escape character  "\\003\", get unexpected value](https://api.github.com/repos/json-c/json-c/issues/518)  
[Add test case obj token](https://api.github.com/repos/json-c/json-c/issues/519)  
[Adding type uint64](https://api.github.com/repos/json-c/json-c/issues/520)  
[build cmake windows 10](https://api.github.com/repos/json-c/json-c/issues/521)  
[update json_visit testcase](https://api.github.com/repos/json-c/json-c/issues/522)  
[update tsetcase for tokener_c](https://api.github.com/repos/json-c/json-c/issues/523)  
[Increase coverage](https://api.github.com/repos/json-c/json-c/issues/524)  
[update pointer test case](https://api.github.com/repos/json-c/json-c/issues/525)  
[Increased the test coverage of printbuf.c 82% to 92%.](https://api.github.com/repos/json-c/json-c/issues/526)  
[Arraylist testcase](https://api.github.com/repos/json-c/json-c/issues/527)  
[Solve issue #108. Skip \u0000 while parsing.](https://api.github.com/repos/json-c/json-c/issues/528)  
[Increased the test coverage of json_c_version.c 0% to 100%.](https://api.github.com/repos/json-c/json-c/issues/529)  
[validate utf-8 string before parse](https://api.github.com/repos/json-c/json-c/issues/530)  
[validate utf-8 string  ](https://api.github.com/repos/json-c/json-c/issues/531)  
[json_object_object_get_ex returning the original object](https://api.github.com/repos/json-c/json-c/issues/532)  
[Fix "make check"](https://api.github.com/repos/json-c/json-c/issues/533)  
[short string optimization: excessive array length](https://api.github.com/repos/json-c/json-c/issues/535)  
[add json_object_new_null()](https://api.github.com/repos/json-c/json-c/issues/536)  
[update shortstring and arraylist parameters](https://api.github.com/repos/json-c/json-c/issues/538)  
[double serializes to the old value after set_double](https://api.github.com/repos/json-c/json-c/issues/539)  
[add coveralls auto tool to json-c](https://api.github.com/repos/json-c/json-c/issues/541)  
[add uint64 data to json-c](https://api.github.com/repos/json-c/json-c/issues/542)  
[Readme](https://api.github.com/repos/json-c/json-c/issues/543)  
[Increase distcheck target in cmake](https://api.github.com/repos/json-c/json-c/issues/544)  
[add doc target in cmake](https://api.github.com/repos/json-c/json-c/issues/545)  
[Add uninstall target in cmake](https://api.github.com/repos/json-c/json-c/issues/546)  
[modify json-c default build type, and fix up the assert() errors in t…](https://api.github.com/repos/json-c/json-c/issues/547)  
[Solve some problems about cmake build type (debug/release)](https://api.github.com/repos/json-c/json-c/issues/548)  
[lib installation issues](https://api.github.com/repos/json-c/json-c/issues/549)  
[Format codes with clang-format tool?](https://api.github.com/repos/json-c/json-c/issues/550)  
[Allow hexadecimal number format convention parsing](https://api.github.com/repos/json-c/json-c/issues/551)  
[Fix/clang ubsan](https://api.github.com/repos/json-c/json-c/issues/553)  
[RFC 8259 compatibility mode](https://api.github.com/repos/json-c/json-c/issues/554)  
[Format json-c with clang-format tool](https://api.github.com/repos/json-c/json-c/issues/555)  
[Fixes various Wreturn-type and Wimplicit-fallthrough errors on Mingw-w64](https://api.github.com/repos/json-c/json-c/issues/556)  
[Add option in CMAKE to not build documentation](https://api.github.com/repos/json-c/json-c/issues/557)  
[modify the doc target message](https://api.github.com/repos/json-c/json-c/issues/558)  
[json_c_visit() not exported on Windows](https://api.github.com/repos/json-c/json-c/issues/559)  
[error: implicit declaration of function '_strtoi64'](https://api.github.com/repos/json-c/json-c/issues/560)  
[add the badge in README.md and test the coveralls](https://api.github.com/repos/json-c/json-c/issues/561)  
[Bugfix and testcases supplements](https://api.github.com/repos/json-c/json-c/issues/562)  
[Changed order of calloc args to match stdlib](https://api.github.com/repos/json-c/json-c/issues/563)  
[Remove autogenerated files](https://api.github.com/repos/json-c/json-c/issues/564)  
[test the CI and ignore this PR](https://api.github.com/repos/json-c/json-c/issues/565)  
[add the json_types.h to Makefile.am](https://api.github.com/repos/json-c/json-c/issues/566)  
[Install json_types.h with autotools build as well.](https://api.github.com/repos/json-c/json-c/issues/567)  
[Adding better support to MinGW](https://api.github.com/repos/json-c/json-c/issues/568)  
[Handling of -Bsymbolic-function in CMakeLists.txt is deficient](https://api.github.com/repos/json-c/json-c/issues/569)  
[CMake: Bump SONAME to 5.](https://api.github.com/repos/json-c/json-c/issues/571)  
[Small fixes to CMakeLists](https://api.github.com/repos/json-c/json-c/issues/572)  
[Fix coveralls submission.](https://api.github.com/repos/json-c/json-c/issues/573)  
[autogen.sh missing from repository](https://api.github.com/repos/json-c/json-c/issues/574)  
[Small cosmetics.](https://api.github.com/repos/json-c/json-c/issues/575)  
[Test coverage for json_c_version.](https://api.github.com/repos/json-c/json-c/issues/576)  
[Be verbose on failing json_c_version test.](https://api.github.com/repos/json-c/json-c/issues/577)  
[CMake: Install pkgconfig file in proper location by default](https://api.github.com/repos/json-c/json-c/issues/578)  
[Enforce strict prototypes.](https://api.github.com/repos/json-c/json-c/issues/579)  
[Fix CMake tests for enforced strict prototypes.](https://api.github.com/repos/json-c/json-c/issues/580)  
[CMakeLists: do not enforce strict prototypes on Windows.](https://api.github.com/repos/json-c/json-c/issues/581)  