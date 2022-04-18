# TerPatcher
I saw `termux` as content provider and it's root directory can be mounted in `mix` file manager.  And there is an app called `LuckyPatcher` that decompiles and recompiles apps with patches like 'remove g-ads' or 'remove in-app purchases' etc. So total sum idea is to create an app that will insert a patch that patch will share patched app's root directory as content provider. (simple words: I wanna get into root, without root, thanks!)

**features**:
1. simple terminal that can access the root(data/data/app_name) directory (this terminal can be launched from activity launcher applications or may be we can install it separately as `ter_app_name`)
2. content provider patch so we can access data/data/app_name directly

**use cases**:
- I have heard that there exists some software that can decrypt the `.db` files of whatsapp if we have root access(I guess they are using some key from the /data/data/com.whataspp) directory.
- Most apps have their top secrets in `/data/data/app_name`(🤔👽️)


BTW.. I found one app that does the same ... google it.
