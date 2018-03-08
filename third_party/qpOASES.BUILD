licenses(["notice"])

package(default_visibility = ["//visibility:public"])

licenses(["notice"])

exports_files(["googletest/LICENSE"])

cc_library(
    name = "qpOASES",
    srcs = [
        "src/BLASReplacement.cpp",
        "src/Bounds.cpp",
        "src/Constraints.cpp",
        "src/Flipper.cpp",
        "src/Indexlist.cpp",
        "src/LAPACKReplacement.cpp",
        "src/Matrices.cpp",
        "src/MessageHandling.cpp",
        "src/OQPinterface.cpp",
        "src/Options.cpp",
        "src/QProblem.cpp",
        "src/QProblemB.cpp",
        "src/SQProblem.cpp",
        "src/SQProblemSchur.cpp",
        "src/SolutionAnalysis.cpp",
        "src/SparseSolver.cpp",
        "src/SubjectTo.cpp",
        "src/Utils.cpp",
    ],
    hdrs = [
        "include/qpOASES.hpp",
        "include/qpOASES/Bounds.hpp",
        "include/qpOASES/Bounds.ipp",
        "include/qpOASES/Constants.hpp",
        "include/qpOASES/ConstraintProduct.hpp",
        "include/qpOASES/Constraints.hpp",
        "include/qpOASES/Constraints.ipp",
        "include/qpOASES/Flipper.hpp",
        "include/qpOASES/Indexlist.hpp",
        "include/qpOASES/Indexlist.ipp",
        "include/qpOASES/LapackBlasReplacement.hpp",
        "include/qpOASES/Matrices.hpp",
        "include/qpOASES/MessageHandling.hpp",
        "include/qpOASES/MessageHandling.ipp",
        "include/qpOASES/Options.hpp",
        "include/qpOASES/QProblem.hpp",
        "include/qpOASES/QProblem.ipp",
        "include/qpOASES/QProblemB.hpp",
        "include/qpOASES/QProblemB.ipp",
        "include/qpOASES/SQProblem.hpp",
        "include/qpOASES/SQProblem.ipp",
        "include/qpOASES/SQProblemSchur.hpp",
        "include/qpOASES/SQProblemSchur.ipp",
        "include/qpOASES/SparseSolver.hpp",
        "include/qpOASES/SubjectTo.hpp",
        "include/qpOASES/SubjectTo.ipp",
        "include/qpOASES/Types.hpp",
        "include/qpOASES/UnitTesting.hpp",
        "include/qpOASES/Utils.hpp",
        "include/qpOASES/Utils.ipp",
        "include/qpOASES/extras/OQPinterface.hpp",
        "include/qpOASES/extras/SolutionAnalysis.hpp",
        "include/qpOASES/extras/SolutionAnalysis.ipp",
    ],
    copts = [
        "-Wall",
        "-pedantic",
        "-Wshadow",
        "-Wfloat-equal",
        "-O3",
        "-Wconversion",
        "-Wsign-conversion",
        "-fPIC",
        "-DLINUX",
        "-DSOLVER_NONE",
        "-D__NO_COPYRIGHT__",
    ],
    include_prefix = "qpOASES",
    includes = [
        ".",
        "include",
        "src",
    ],
    visibility = ["//visibility:public"],
)
