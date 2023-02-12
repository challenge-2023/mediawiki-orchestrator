# mediawiki-orchestrator

`
time ansible-playbook playbook.yml -e aws_access_key="<aws-access-key>" -e aws_secret_key="<aws-secret-key>" -e cust_id="<a unique prefix 3-4 char>" -e state=present -t "create"
`

For example 

time ansible-playbook playbook.yml -e aws_access_key="ABCDEFGHIJ1234567890" -e aws_secret_key="qwertyui1234567zxcvbnD" -e cust_id="abc" -e state=present -t "create"
