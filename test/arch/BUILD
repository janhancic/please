# A set of rules to exercise the cross-compiling code.
genrule(
    name = 'target_rule',
    outs = ['target_out'],
    srcs = [':either_rule'],
    cmd = 'cat $SRCS > $OUT',
    arch = 'test_amd64',
)

genrule(
    name = 'either_rule',
    outs = ['either_out'],
    cmd = 'echo $ARCH > $OUT',
)
