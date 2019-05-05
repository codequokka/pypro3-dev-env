pypro3-dev-env
==============

Provisioning devlopment environment for pypro3 book([Pythonプロフェッショナルプログラミング 第3版][1])
with vagrant and ansible

Requirements(macOS)
------------
- Install Vagrant, virtualbox, ansible
```console
$ brew cask install vagrant
$ brew cask install virtualbox
$ brew install ansible
```

Usage
------------
- Create vm then log in
  - Vagrant installs ansible role([codequokka.ansible_role_pypro3][2]) then provsions
```console
$ vagrant up
$ vagrant ssh
```

[1]:https://www.amazon.co.jp/Python%E3%83%97%E3%83%AD%E3%83%95%E3%82%A7%E3%83%83%E3%82%B7%E3%83%A7%E3%83%8A%E3%83%AB%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0-%E7%AC%AC3%E7%89%88-%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E3%83%93%E3%83%BC%E3%83%97%E3%83%A9%E3%82%A6%E3%83%89/dp/4798053821/ref=pd_sbs_14_1/355-5596879-2633321?_encoding=UTF8&pd_rd_i=4798053821&pd_rd_r=49ce03b6-6c8c-11e9-a57a-e3364931b9ea&pd_rd_w=28WM9&pd_rd_wg=Kcu34&pf_rd_p=ad2ea29d-ea11-483c-9db2-6b5875bb9b73&pf_rd_r=5ECB3M52PQ0SDXKCVW8Z&psc=1&refRID=5ECB3M52PQ0SDXKCVW8Z

[2]:https://galaxy.ansible.com/codequokka/ansible_role_pypro3
