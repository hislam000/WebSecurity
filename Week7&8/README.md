# Project 7 - WordPress Pentesting

Time spent: **6** hours spent in total

> Objective: Find, analyze, recreate, and document **3 vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. WordPress => 4.2 – Authenticated stored Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.2
    - Fixed in version: 4.3
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Make a new post >> Write the following javascript"<script type="text/javascript">alert("XSS");</script>" Publish it >> Then view to post!
 
2. WordPress =>2.5 – 4.6 - Authenticated Stored Cross-Site Scripting (XSS) via Image frame 
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.2
    - Fixed in version: 4.6.1
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Upload a new image (.png) in library >> go to library >> Then click on that image >> Then in the title section, add the following JavaScript "<IMG SRC="#" ONERROR="alert('XSS')"/>" Then clck next to the image name.
 
3. WordPress => 4.2 - User Authentication 
  - [ ] Summary: 
    - Vulnerability types:User Authentication
    - Fixed in version: 4.2
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Type "admin" as username and provide different password >> Try different name as username >> Then type different password as password.
  
## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2019] [Hasibul Islam]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
