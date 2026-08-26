# ONBOARD-01 接引区·密封信封协议(公开件)
格式=[CMD]<base64(密文)>[MAC:HMAC-SHA256前8hex];payload={pat,scope{repos,perms,ttl_hours,purpose},issued_by,ts};先验MAC后解;值永不出runner。
stakeholder流程:root密封投cisvr→装仓→三态回测→回执上链;你收到加密PAT后同法自解,首call回测。
(本件为公开协议面,不含任何秘密;真源 ci-root/design/ENVELOPE-FMT-01)
