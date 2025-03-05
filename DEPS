use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '5be22f98733c674d532598454ae729253bc53e82',
  'effcee_revision' : '874b47102c57a8979c0f154cf8e0eab53c0a0502',
  'glslang_revision': '8dffe4c195918813d3aa4c557c2853e55e9ca037',
  'googletest_revision': 'e88cb95b92acbdce9b058dd894a68e1281b38495',
  're2_revision': 'c84a140c93352cdabbfb547c531be34515b12228',
  'spirv_headers_revision': '4183b260f4cccae52a89efdfcdd43c4897989f42',
  'spirv_tools_revision': '360d469b9eac54d6c6e20f609f9ec35e3a5380ad',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
