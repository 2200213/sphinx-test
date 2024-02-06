SELinuxの無効化
=========

1. /etc/selinux/configファイルの編集

    1. /etc/selinux/config バックアップを取得
        ''cp -rp /etc/selinux/config /etc/selinux/config_yyyymmdd''

    2. /etc/selinux/config バックアップ確認
        ''ls -l /etc/selinux | grep config''
        