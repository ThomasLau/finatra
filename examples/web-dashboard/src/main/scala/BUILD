scala_library(
  dependencies=[
    '3rdparty/jvm/ch/qos/logback:logback-classic',
    '3rdparty/jvm/com/google/inject/extensions:guice-assistedinject',
    '3rdparty/jvm/com/google/inject/extensions:guice-multibindings',
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/javax/inject:javax.inject',
    '3rdparty/jvm/net/codingwell:scala-guice',
    '3rdparty/jvm/org/slf4j:slf4j-api',
    'finagle/finagle-http/src/main/scala',
    'finagle/finagle-zipkin/src/main/scala',
    'finatra/examples/web-dashboard/src/main/resources',
    'finatra/examples/web-dashboard/src/main/webapp',
    'finatra/http/src/main/java',
    'finatra/http/src/main/scala',
    'finatra/httpclient/src/main/scala',
    'finatra/inject/inject-app/src/main/scala',
    'finatra/inject/inject-core/src/main/scala',
    'finatra/inject/inject-server/src/main/scala',
    'finatra/inject/inject-thrift-client/src/main/scala',
    'finatra/inject/inject-utils/src/main/scala',
    'twitter-server/src/main/scala',
    'util/util-app/src/main/scala',
    'util/util-core/src/main/scala',
    'util/util-logging/src/main/scala',
    'util/util-slf4j-api/src/main/scala',
  ],
  fatal_warnings=True,
  sources=globs(
    'com/twitter/web/dashboard/*.scala',
    'com/twitter/web/dashboard/controllers/*.scala',
    'com/twitter/web/dashboard/views/*.scala',
  ),
)
