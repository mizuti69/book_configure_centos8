# Summary

* [Redhat8 / CentOS8 設定手順書](./README.md)
* [OSのインストール](1.manual_install/index.md)
  * [はじめに](1.manual_install/1.premise.md)
  * [インストール](1.manual_install/2.install.md)
  * [サブスクリプション設定](1.manual_install/3.subscribe.md)
* [OS基本設定](2.configure/index.md)
  * [ネットワーク設定](2.configure/1.network/index.md)
    * [NICの設定](2.configure/1.network/1.network_nic.md)
    * [ホスト名の設定](2.configure/1.network/2.network_hostname.md)
    * [ネットワークセキュリティ設定](2.configure/1.network/3.network_security.md)
  * [SELinuxの設定](2.configure/1.configure_selinux.md)
  * [SYSTEMDによるサーバ管理](2.configure/2.configure_systemctl.md)
  * [システムロケール](2.configure/3.configure_locale.md)
  * [システム時刻](2.configure/4.configure_time.md)
  * [cron設定](2.configure/5.configure_cron.md)
  * [ログローテート](2.configure/6.configure_logrotate.md)
  * [カーネルパニック対応](2.configure/7.configure_panic.md)
  * [SYSTEMDログレベルの変更](2.configure/8.configure_systemd.md)
  * [運用用設定](2.configure/9.configure_operation.md)
  * [rsyslogの設定](2.configure/10.configure_rsyslog.md)
  * [Cockpitのインストール](2.configure/11.configure_cockpit.md)  
* [アカウント管理](3.user/index.md)
  * [ユーザーデフォルトの設定](3.user/1.user_default.md)
  * [ユーザー・グループの作成](3.user/2.user_create.md)
* [セキュリティ設定](4.security/index.md)
  * [ユーザー権限昇格設定](4.security/1.security_sudo.md)
  * [不要なサービスの停止](4.security/2.security_service.md)
  * [firewalld](4.security/3.security_firewalld.md)
* [SSHサーバ設定](5.ssh/index.md)
  * [基本設定](5.ssh/1.ssh_config.md)
  * [認証設定](5.ssh/2.ssh_auth.md)
  * [SFTP設定](5.ssh/3.ssh_sftp.md)
* [時刻同期設定](6.timedate/index.md)
  * [chrony設定](6.timedate/1.timedate_chrony.md)
* [セキュリティパッチの適用](7.update/index.md)
  * [アップデートの適応](7.update/1.update_dnf.md)
* [SMTPサーバ設定](8.smtp/index.md)
  * [Postfixのインストール](8.smtp/1.smtp_config.md)
  * [メールサーバ用の設定](8.smtp/2.smtp_server.md)
  * [メールクライアント・転送用の設定](8.smtp/3.smtp_client.md)
  * [送信制限](8.smtp/4.smtp_transport.md)
  * [Postfix メールアドレス制御](8.smtp/5.smtp_address_limit.md)
  * [Postfix接続数制限](8.smtp/6.smtp_client_limit.md)
  * [ブラックリスト制限](8.smtp/7.smtp_blacklist.md)
* [その他](9.tips/index.md)
  * [便利ツール](9.tips/1.tips_tools.md)
  * [Fsecure Linux セキュリティ コマンドラインエディション](9.tips/2.tips_fsecure.md)
  * [sysstatの設定](9.tips/3.tips_sysstat.md)
  * [Auditの設定](9.tips/4.tips_audit.md)
  * [パスワード有効期限の設定](9.tips/5.tips_chage.md)  
  * [NFS設定](9.tips/6.tips_nfs.md)  
