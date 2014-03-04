heroku-buildpack-gdb
====================

Use gdb on Heroku! Happy debugging!

How to use
----------

### Specify buildpack

```
heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git
```

### Add .buildpacks

```
cat << EOF > .buildpacks
https://github.com/keiko713/heroku-buildpack-gdb.git
https://github.com/heroku/heroku-buildpack-ruby.git
EOF
```
