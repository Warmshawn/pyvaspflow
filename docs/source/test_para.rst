============
测试参数
============

这里我们提供了一些测试参数的命令.


测试截断能
============

这里是测试截断能的命令::

    $ pyvasp test_encut  POSCAR -s 0.8 -e 1.3 -t 30


这里 ``-s`` 是  0.8*max_encut, encut 是你的赝势中的最大的 ``ENMAX`` ,
类似的 ``-e`` 是 1.3*max_encut, ``-t`` 就是间隔. 这个命令也是支持 ``-a`` 这个参数的, 你可以制定一些其他参数.



测试k点
============

这里是测试k-mesh的命令::

    $ pyvasp test_kpts  POSCAR -s 1000 -e 3000 -t 200

这里与上面是类似的, ``-s`` 是起始的kppa, ``-e`` 是最终的kppa, ``-t`` 指定了间隔, 同样的也支持 ``-a`` 参数.
