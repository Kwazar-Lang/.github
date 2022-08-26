<!--
Copyright 2022 Kwazar Lang Devs

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Final decision on implementation
On August 26, 2022, we decided to change the main implementation of the language. The implementation switches from the interpreter to the compiler. And there will be more than one: a reference compiler that provides a more flexible syntax and convenience, and a compiler based on LLVM that provides high speed with a slightly more complex syntax.

At the moment, work is underway with the reference compiler, it will be brought to the stable version first. After it , a compiler based on LLVM will be presented.

### Watch the [news](https://github.com/Kwazar-Lang/.github/blob/main/news/NEWSMAP.md) so that you don't miss anything.
