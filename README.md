# Bugbounty（赏金技巧）

<h3>loT高频率账户密码</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/IoT.png" alt="Image" style="max-width: 100%;" class="">

<h3>git字典 / svn字典</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/git.svn.png" alt="Image" style="max-width: 100%;" class="">

<h3>重定向dorks</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/dorks.png" alt="Image" style="max-width: 100%;" class="">

<h3>Top25 ssrf dorks</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/ssrf%20dorks.png" alt="Image" style="max-width: 100%;" class="">

<h3>SSRF Bypass</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/SSRF%20Bypass.png" alt="Image" style="max-width: 100%;" class="">

<h3>Top 25 RCE</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/RCE.png" alt="Image" style="max-width: 100%;" class="">

<h3>Top 25 LFI</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/LFI.png" alt="Image" style="max-width: 100%;" class="">

<h3>403 Bypass</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/403%20bypass.png" alt="Image" style="max-width: 100%;" class="">

<h3>.json信息泄露</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/json.png" alt="Image" style="max-width: 100%;" class="">

<h3>使用grep快速去除JS垃圾数据</h3>
curl http://host/file.js | grep -Eo "(http|https)://[a-zA-Z0-9./?=_-]*"*

cat file | grep -Eo "(http|https)://[a-zA-Z0-9./?=_-]*"*

<h3>CI Bypass</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/CI%20Bypass.png" alt="Image" style="max-width: 100%;" class="">

<h3>查询是否存在heartbleed漏洞</h3>
cat list.txt | while read line ; do echo "QUIT" | openssl s_client -connect $line:443 2>&1 | grep 'server extension "heartbeat" (id=15)' || echo $line: safe; done


<h3>sql注入检测</h3>
<img src="https://github.com/CKevens/Bugbounty/blob/main/SQL%20injet.png" alt="Image" style="max-width: 100%;" class="">

<h3>favicon信息</h3>
https://github.com/devanshbatham/FavFreak

>cat urls.txt | python3 favfreak.py -o output



