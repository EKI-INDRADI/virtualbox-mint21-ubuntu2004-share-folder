## Tutorial : 

<details>
  <summary>SETUP VM PROPERTIES</summary>

```sh

virtualbox -> vm properties -> general -> advanced -> Bidirectional

```

</details>

<details>
  <summary>SETUP VIRTUALBOX MENU</summary>
  
```sh

sudo  ./autorun.sh   

```

or 

```sh

sudo ./VBOXLinuxAdditions.run

```
</details>

<details>
  <summary>SHARE FILE & FIX PERMISSION ISSUE</summary>

```sh

virtualbox -> vm properties -> share folder 

Folder Path : D:\___CODE_GIT2\CODE
Folder Name : CODE
Mount Point : /home/CODE

Permanent

```

Not permanent

```sh

sudo mount -t vboxsf -o rw,uid=1000,gid=1000 CODE /home/CODE

```

Permanent

```sh

sudo nano /etc/fstab

```


```sh

CODE /home/CODE vboxsf rw,uid=1000,gid=1000 0 0

```

</details>



## EKI INDRADI

"TIME > KNOWLEDGE > MONEY". #2024_3_DIGIT_MOTIVATION

## Reference : 

:link: [Reference 1](https://www.linuxbabe.com/linux-mint/install-virtualbox-guest-additions-in-linux-mint)
:link: [Reference 2](https://forums.virtualbox.org/viewtopic.php?t=79965)


