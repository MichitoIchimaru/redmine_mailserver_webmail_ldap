FROM osixia/openldap:latest

# 初期データを作成するためのLDIFファイルをコンテナにコピーする。
ADD data/init.ldif /container/service/slapd/assets/config/bootstrap/ldif/custom
