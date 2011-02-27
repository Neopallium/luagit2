luagit2
=======

LuaGit2 has move to a new home at [https://github.com/libgit2/luagit2](https://github.com/libgit2/luagit2)

Installing
----------

### Install lua-git2:

	curl -O "https://github.com/libgit2/luagit2/raw/master/lua-git2-scm-0.rockspec"
	
	luarocks install lua-git2-scm-0.rockspec


To re-generating the bindings
-----------------------------

You will need to install LuaNativeObjects and set the CMake variable `USE_PRE_GENERATED_BINDINGS` to FALSE.
By default CMake will use the pre-generated bindings that are include in the project.

Build Dependencies
------------------

Optional dependency for re-generating Lua bindings from `*.nobj.lua` files:

* [LuaNativeObjects](https://github.com/Neopallium/LuaNativeObjects), this is the bindings generator used to convert the `*.nobj.lua` files into a native Lua module.

