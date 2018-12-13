justinkwony.github.io
=====================
(2018.12.12)
Tibero 데이터베이스 가져오기(Import)할때
Specified schema object was not found. at line 1, column 42: SELECT OWNER, TABLE_NAME, COMMENTS FROM SYS.ALL_TAB_COMMENTS 에러가 발생하는 것을 수정했습니다.
schema명을 SYS 에서 SYSCAT 으로 변경했습니다.

*설치시 오류가 나는 경우<br>
*Install New Software... 에서 update-site를 넣었는데, There are no categorized items 나올때 : [ ] Group items by category 를 해제<br>
*수정된 plugin과 기존 버전 정보가 같기때문에 이미 설치되어 있다면 Install 화면에서 What is already installed? 를 찾아서 ERMaster-NHIT 제거후 eclipse 설치폴더 root에 있는 artifacts.xml에서 org.insightech.er, org.insightech.er.feature 항목을 제거 후 재설치<br>
*그래도 않되면 zip파일을 풀어서 eclipse/plugins에 jar파일을 복사 후 재시작

(2018.09.06)
원 제작자가 sourceforge(https://sourceforge.net/projects/ermaster)를 통해 한글 지원 버전을 배포하고 있습니다.
그런데, 국산DBMS(Tibero, CUBRID) 지원 부분은 하다만듯 합니다. class 파일을 제외한 프로퍼티 류의 소스만 일부 반영되어 있어 전체소스를 github에 공개합니다.
Tibero, CUBRID 지원과 한글 테이블정의서(xls) 포함되었습니다.
http://justinkwony.github.io<br>

======================

Add Eclipse Update site for ERMaster-NHIT

Copyright 2009 insightech.org
Copyright 2014 nongyhupit.com

Licensed under the Apache License, Version 2.0 (the &quot;License&quot;);
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an &quot;AS IS&quot; BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
