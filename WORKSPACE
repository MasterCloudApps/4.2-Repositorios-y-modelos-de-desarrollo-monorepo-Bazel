load('@bazel_tools//tools/build_defs/repo:http.bzl', 'http_archive')

RULES_JVM_EXTERNAL_TAG = '4.1'
RULES_JVM_EXTERNAL_SHA = 'f36441aa876c4f6427bfb2d1f2d723b48e9d930b62662bf723ddfb8fc80f0140'

http_archive(
  name = 'rules_jvm_external',
  strip_prefix = 'rules_jvm_external-%s' % RULES_JVM_EXTERNAL_TAG,
  sha256 = RULES_JVM_EXTERNAL_SHA,
  url = 'https://github.com/bazelbuild/rules_jvm_external/archive/%s.zip' % RULES_JVM_EXTERNAL_TAG,
)

load('@rules_jvm_external//:defs.bzl', 'maven_install')

maven_install(
  artifacts = [
    'org.springframework.boot:spring-boot-autoconfigure:2.4.1',
    'org.springframework.boot:spring-boot-starter-web:2.4.1',
    'org.springframework.boot:spring-boot:2.4.1',
    'org.springframework.data:spring-data-jpa:2.4.2',
    'org.springframework:spring-web:5.3.2',
    'org.springframework:spring-tx:5.3.2',
    'org.springframework:spring-context:5.3.2',
    'org.springframework:spring-jdbc:5.3.2',
    'org.springframework:spring-core:5.3.2',
    'org.springframework:spring-beans:5.3.2',
    'org.springframework.boot:spring-boot-starter-mustache:2.4.1',
    'org.springframework.boot:spring-boot-starter-data-jpa:2.4.1',
    'org.springframework.boot:spring-boot-starter-logging:2.4.1',
    'com.h2database:h2:1.4.200',
    'jakarta.annotation:jakarta.annotation-api:1.3.5',
    'jakarta.persistence:jakarta.persistence-api:2.2.3',
    'jakarta.xml.bind:jakarta.xml.bind-api:2.3.3'
  ],
  repositories = [
    'https://repo1.maven.org/maven2',
  ],
  fetch_sources = True,
)
