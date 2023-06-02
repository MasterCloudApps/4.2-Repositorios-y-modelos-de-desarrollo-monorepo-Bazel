java_binary(
  name = 'books',
  main_class = 'es.urjc.code.daw.library.Application',
  srcs = glob(['src/**/*.java']),
  resources = glob(["src/main/resources/**"]),
  deps = [
    '@maven//:org_springframework_boot_spring_boot',
    '@maven//:org_springframework_boot_spring_boot_autoconfigure',
    '@maven//:org_springframework_boot_spring_boot_starter_web',
    '@maven//:org_springframework_spring_web',
    '@maven//:org_springframework_spring_context',
    '@maven//:org_springframework_spring_core',
    '@maven//:org_springframework_spring_tx',
    '@maven//:org_springframework_spring_beans',
    '@maven//:org_springframework_spring_jdbc',
    '@maven//:org_springframework_data_spring_data_jpa',
    '@maven//:org_springframework_boot_spring_boot_starter_mustache',
    '@maven//:org_springframework_boot_spring_boot_starter_data_jpa',
    '@maven//:com_h2database_h2',
    '@maven//:jakarta_annotation_jakarta_annotation_api',
    '@maven//:jakarta_persistence_jakarta_persistence_api',
    '@maven//:jakarta_xml_bind_jakarta_xml_bind_api'
  ],
)