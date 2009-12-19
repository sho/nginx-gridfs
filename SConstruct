# -*- mode: python; -*-
import os

libs = [os.environ.get("LIBMONGOCLIENT"),
        os.environ.get("LIBBOOST_THREAD"),
        os.environ.get("LIBBOOST_FILESYSTEM")]

if "LIBBOOST_SYSTEM" in os.environ:
    libs.append(os.environ.get("LIBBOOST_SYSTEM"))

Object("gridfs_c_helpers.cpp",
       CPPPATH=[os.environ.get("MONGO_INCLUDE_PATH"), os.environ.get("BOOST_INCLUDE_PATH")],
<<<<<<< HEAD
       LIBS=[os.environ.get("LIBMONGOCLIENT"),
             os.environ.get("LIBBOOST_THREAD"),
             os.environ.get("LIBBOOST_FILESYSTEM"),
             os.environ.get("LIBBOOST_SYSTEM")])

=======
       LIBS=libs)
>>>>>>> upstream/master
