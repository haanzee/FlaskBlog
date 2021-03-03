pip install flask-wtf
pip install email_validator

===
to generate secrets key
go python
import secrets
secrets.token_hex(16)

3df7dc3ec10215df9580e8945c523574


Jaswinder Singh
haanzee@gmail.com
admin123

Ram Singh
abc@gmail.com
admin123


password token
================

from itsdangerous import TimeJSONWebSignatureSerializer as TimeJSONWebSignatureSerializer
s = Seriallizer('secret', 30)
token = s.dumps({'user_id':1}).decode('utf-8')
token

s.loads(token)

==============