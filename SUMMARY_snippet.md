* Recipes
  * [Java](reference/recipes/java/README.md)
    * [Add ASLv2 license header.](reference/recipes/java/addapache2licenseheader.md)
    * [Add license header](reference/recipes/java/addlicenseheader.md)
    * [Change method name](reference/recipes/java/changemethodname.md)
    * [Change method target to static](reference/recipes/java/changemethodtargettostatic.md)
    * [Change method target to variable](reference/recipes/java/changemethodtargettovariable.md)
    * [Change package](reference/recipes/java/changepackage.md)
    * [Change type](reference/recipes/java/changetype.md)
    * [Delete method argument](reference/recipes/java/deletemethodargument.md)
    * [Order imports](reference/recipes/java/orderimports.md)
    * [Remove annotation](reference/recipes/java/removeannotation.md)
    * [Remove unused imports](reference/recipes/java/removeunusedimports.md)
    * [Reorder method arguments](reference/recipes/java/reordermethodarguments.md)
    * [Use static import](reference/recipes/java/usestaticimport.md)
    * [Cleanup](reference/recipes/java/cleanup/README.md)
      * [Code cleanup](reference/recipes/java/cleanup/cleanup.md)
      * [Covariant equals](reference/recipes/java/cleanup/covariantequals.md)
      * [Remove empty blocks](reference/recipes/java/cleanup/emptyblock.md)
      * [Equals avoids null](reference/recipes/java/cleanup/equalsavoidsnull.md)
      * [Explicit initialization](reference/recipes/java/cleanup/explicitinitialization.md)
      * [Finalize local variables](reference/recipes/java/cleanup/finalizelocalvariables.md)
      * [Hide utility class constructor](reference/recipes/java/cleanup/hideutilityclassconstructor.md)
      * [Method name casing](reference/recipes/java/cleanup/methodnamecasing.md)
      * [Modifier order](reference/recipes/java/cleanup/modifierorder.md)
      * [Use primitive wrapper `valueOf` method](reference/recipes/java/cleanup/primitivewrapperclassconstructortovalueof.md)
      * [Redundant file creation](reference/recipes/java/cleanup/redundantfilecreation.md)
      * [Simplify boolean expression](reference/recipes/java/cleanup/simplifybooleanexpression.md)
      * [Simplify boolean return](reference/recipes/java/cleanup/simplifybooleanreturn.md)
      * [Static methods not final](reference/recipes/java/cleanup/staticmethodnotfinal.md)
      * [Unnecessary explicit type arguments](reference/recipes/java/cleanup/unnecessaryexplicittypearguments.md)
      * [Remove unnecessary parentheses](reference/recipes/java/cleanup/unnecessaryparentheses.md)
      * [Unnecessary throws](reference/recipes/java/cleanup/unnecessarythrows.md)
      * [Use diamond operator](reference/recipes/java/cleanup/usediamondoperator.md)
    * [Example](reference/recipes/java/example/README.md)
      * [Generate getter](reference/recipes/java/example/generategetter.md)
    * [Format](reference/recipes/java/format/README.md)
      * [Format Java code](reference/recipes/java/format/autoformat.md)
      * [Blank lines](reference/recipes/java/format/blanklines.md)
      * [Normalize format](reference/recipes/java/format/normalizeformat.md)
      * [Remove trailing whitespace](reference/recipes/java/format/removetrailingwhitespace.md)
      * [Spaces](reference/recipes/java/format/spaces.md)
      * [Tabs and indents](reference/recipes/java/format/tabsandindents.md)
      * [Wrapping and braces](reference/recipes/java/format/wrappingandbraces.md)
    * [Migrate](reference/recipes/java/migrate/README.md)
      * [Migrate OpenRewrite 6.x names](reference/recipes/java/migrate/migrateopenrewrite6xnames.md)
    * [Search](reference/recipes/java/search/README.md)
      * [Find plain text secrets](reference/recipes/java/search/findsecrets.md)
      * [Find annotations](reference/recipes/java/search/findannotations.md)
      * [Find fields](reference/recipes/java/search/findfields.md)
      * [Find methods](reference/recipes/java/search/findmethods.md)
      * [Find text](reference/recipes/java/search/findtext.md)
      * [Find types](reference/recipes/java/search/findtypes.md)
      * [Has types](reference/recipes/java/search/hastypes.md)
      * [Result of method call ignored](reference/recipes/java/search/resultofmethodcallignored.md)
    * [Security](reference/recipes/java/security/README.md)
      * [Java security best practices](reference/recipes/java/security/javasecuritybestpractices.md)
      * [Allows attacker to create a directory with elevated permissions.](reference/recipes/java/security/resultoffilemkdirsignored.md)
      * [XML parser XXE vulnerability](reference/recipes/java/security/xmlparserxxevulnerability.md)
    * [Spring](reference/recipes/java/spring/README.md)
      * [Bean Methods Not Public](reference/recipes/java/spring/beanmethodsnotpublic.md)
      * [Remove Implicit Web Annotation Names](reference/recipes/java/spring/implicitwebannotationnames.md)
      * [Remove Autowired Annotation from MethodDeclarations](reference/recipes/java/spring/noautowired.md)
      * [No `@RequestMapping` annotations](reference/recipes/java/spring/norequestmappingannotation.md)
      * [Boot2](reference/recipes/java/spring/boot2/README.md)
        * [JUnit Jupiter migration from JUnit 4.x for Spring Boot 2.x projects](reference/recipes/java/spring/boot2/springboot2junit4to5migration.md)
        * [Spring Boot 2.x best practices](reference/recipes/java/spring/boot2/springboot2bestpractices.md)
        * [Spring Boot 2.x migration from Spring Boot 1.x](reference/recipes/java/spring/boot2/springboot1to2migration.md)
        * [Convert multi condition ConditionalOnBean Annotations to AnyNestedCondition](reference/recipes/java/spring/boot2/conditionalonbeananynestedcondition.md)
        * [`@OutputCaptureRule` to `@ExtendWith(OutputCaptureExtension.class)`](reference/recipes/java/spring/boot2/outputcaptureextension.md)
        * [Replace EnvironmentUtils with TestPropertyValues](reference/recipes/java/spring/boot2/replacedeprecatedenvironmenttestutils.md)
        * [RestTemplateBuilderRequestFactory](reference/recipes/java/spring/boot2/resttemplatebuilderrequestfactory.md)
        * [Remove `@SpringExtension` if `@SpringBootTest` is present](reference/recipes/java/spring/boot2/unnecessaryspringextension.md)
        * [Config](reference/recipes/java/spring/boot2/config/README.md)
          * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationProperties_2_0](reference/recipes/java/spring/boot2/config/springbootconfigurationproperties_2_0.md)
          * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationProperties_2_1](reference/recipes/java/spring/boot2/config/springbootconfigurationproperties_2_1.md)
          * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationProperties_2_2](reference/recipes/java/spring/boot2/config/springbootconfigurationproperties_2_2.md)
          * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationProperties_2_3](reference/recipes/java/spring/boot2/config/springbootconfigurationproperties_2_3.md)
          * [Springbootconfigurationyaml](reference/recipes/java/spring/boot2/config/springbootconfigurationyaml/README.md)
            * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationYaml.2_0](reference/recipes/java/spring/boot2/config/springbootconfigurationyaml/2_0.md)
            * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationYaml.2_1](reference/recipes/java/spring/boot2/config/springbootconfigurationyaml/2_1.md)
            * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationYaml.2_2](reference/recipes/java/spring/boot2/config/springbootconfigurationyaml/2_2.md)
            * [org.openrewrite.java.spring.boot2.config.SpringBootConfigurationYaml.2_3](reference/recipes/java/spring/boot2/config/springbootconfigurationyaml/2_3.md)
    * [Testing](reference/recipes/java/testing/README.md)
      * [Assertj](reference/recipes/java/testing/assertj/README.md)
        * [AssertJ best practices](reference/recipes/java/testing/assertj/assertj.md)
        * [Statically import AssertJ's `assertThat`](reference/recipes/java/testing/assertj/staticimports.md)
        * [Migrate JUnit asserts to AssertJ](reference/recipes/java/testing/assertj/junittoassertj.md)
        * [JUnitAssertArrayEquals To AssertThat](reference/recipes/java/testing/assertj/junitassertarrayequalstoassertthat.md)
        * [JUnitAssertEquals To AssertThat](reference/recipes/java/testing/assertj/junitassertequalstoassertthat.md)
        * [JUnit AssertFalse to AssertThat](reference/recipes/java/testing/assertj/junitassertfalsetoassertthat.md)
        * [JUnit AssertNotEquals to AssertThat](reference/recipes/java/testing/assertj/junitassertnotequalstoassertthat.md)
        * [JUnit AssertNotNull to AssertThat](reference/recipes/java/testing/assertj/junitassertnotnulltoassertthat.md)
        * [JUnit AssertNull to AssertThat](reference/recipes/java/testing/assertj/junitassertnulltoassertthat.md)
        * [JUnit AssertSame to AssertThat](reference/recipes/java/testing/assertj/junitassertsametoassertthat.md)
        * [JUnit AssertTrue to AssertThat](reference/recipes/java/testing/assertj/junitasserttruetoassertthat.md)
        * [JUnitFailToAssert to AssertJFail](reference/recipes/java/testing/assertj/junitfailtoassertjfail.md)
      * [Cleanup](reference/recipes/java/testing/cleanup/README.md)
        * [Testing Frameworks best practices](reference/recipes/java/testing/cleanup/bestpractices.md)
        * [Tests should include assertions](reference/recipes/java/testing/cleanup/testsshouldincludeassertions.md)
      * [Hamcrest](reference/recipes/java/testing/hamcrest/README.md)
        * [Add `org.hamcrest:hamcrest` if it is used.](reference/recipes/java/testing/hamcrest/addhamcrestifused.md)
      * [Junit5](reference/recipes/java/testing/junit5/README.md)
        * [JUnit Jupiter best practices](reference/recipes/java/testing/junit5/junit5bestpractices.md)
        * [Statically import JUnit Jupiter assertions](reference/recipes/java/testing/junit5/staticimports.md)
        * [JUnit Jupiter migration from JUnit 4.x](reference/recipes/java/testing/junit5/junit4to5migration.md)
        * [Use `MatcherAssert#assertThat(..)`](reference/recipes/java/testing/junit5/usehamcrestassertthat.md)
        * [Use Mockito JUnit Jupiter extension](reference/recipes/java/testing/junit5/usemockitoextension.md)
        * [Use JUnit Jupiter `@Disabled`](reference/recipes/java/testing/junit5/ignoretodisabled.md)
        * [Assert To Assertions](reference/recipes/java/testing/junit5/asserttoassertions.md)
        * [Category To Tag](reference/recipes/java/testing/junit5/categorytotag.md)
        * [Cleanup JUnit Imports](reference/recipes/java/testing/junit5/cleanupjunitimports.md)
        * [ExpectedException To AssertThrows](reference/recipes/java/testing/junit5/expectedexceptiontoassertthrows.md)
        * [Pragmatists @RunWith(JUnitParamsRunner.class) to JUnit Jupiter Parameterized Tests](reference/recipes/java/testing/junit5/junitparamsrunnertoparameterized.md)
        * [MockitoJUnit to MockitoExtension](reference/recipes/java/testing/junit5/mockitojunittomockitoextension.md)
        * [JUnit4 @RunWith(Parameterized.class) to JUnit Jupiter Parameterized Tests](reference/recipes/java/testing/junit5/parameterizedrunnertoparameterized.md)
        * [Remove JUnit4 @RunWith annotations that do not require an @ExtendsWith replacement.](reference/recipes/java/testing/junit5/removeobsoleterunners.md)
        * [JUnit4 @RunWith to JUnit Jupiter @ExtendWith](reference/recipes/java/testing/junit5/runnertoextension.md)
        * [TemporaryFolder to TempDir](reference/recipes/java/testing/junit5/temporaryfoldertotempdir.md)
        * [Update Before After Annotations](reference/recipes/java/testing/junit5/updatebeforeafterannotations.md)
        * [okhttp3 3.x MockWebserver @Rule To 4.x MockWebServer](reference/recipes/java/testing/junit5/updatemockwebserver.md)
        * [Migrate JUnit4 `@Test` annotations to JUnit5](reference/recipes/java/testing/junit5/updatetestannotation.md)
        * [Migrate from JUnit4 `@FixedMethodOrder` to JUnit5 `@TestMethodOrder`](reference/recipes/java/testing/junit5/usetestmethodorder.md)
      * [Mockito](reference/recipes/java/testing/mockito/README.md)
        * [Mockito 3.x migration from 1.x](reference/recipes/java/testing/mockito/mockito1to3migration.md)
        * [Cleanup Mockito Imports](reference/recipes/java/testing/mockito/cleanupmockitoimports.md)
        * [MockUtils To Static](reference/recipes/java/testing/mockito/mockutilstostatic.md)
  * [Maven](reference/recipes/maven/README.md)
    * [Add Maven dependency](reference/recipes/maven/adddependency.md)
    * [Add Maven plugin](reference/recipes/maven/addplugin.md)
    * [Change Maven dependency scope](reference/recipes/maven/changedependencyscope.md)
    * [Change a Maven project property value.](reference/recipes/maven/changepropertyvalue.md)
    * [Exclude Maven dependency](reference/recipes/maven/excludedependency.md)
    * [Manage dependencies](reference/recipes/maven/managedependencies.md)
    * [Remove Maven dependency](reference/recipes/maven/removedependency.md)
    * [Remove a Maven project property](reference/recipes/maven/removeproperty.md)
    * [Remove redundant explicit dependency versions](reference/recipes/maven/removeredundantdependencyversions.md)
    * [Upgrade Maven dependency version](reference/recipes/maven/upgradedependencyversion.md)
    * [Upgrade Maven parent project version](reference/recipes/maven/upgradeparentversion.md)
    * [Search](reference/recipes/maven/search/README.md)
      * [Maven dependency insight](reference/recipes/maven/search/dependencyinsight.md)
      * [Find Maven dependency](reference/recipes/maven/search/finddependency.md)
      * [Find Maven project properties](reference/recipes/maven/search/findproperties.md)
  * [Properties](reference/recipes/properties/README.md)
    * [Change property key](reference/recipes/properties/changepropertykey.md)
    * [Change properties file property value](reference/recipes/properties/changepropertyvalue.md)
    * [Search](reference/recipes/properties/search/README.md)
      * [Find property](reference/recipes/properties/search/findproperties.md)
  * [Text](reference/recipes/text/README.md)
    * [Change Text](reference/recipes/text/changetext.md)
  * [Xml](reference/recipes/xml/README.md)
    * [Format XML](reference/recipes/xml/autoformat.md)
    * [Search](reference/recipes/xml/search/README.md)
      * [Find XML tags](reference/recipes/xml/search/findtags.md)
  * [Yaml](reference/recipes/yaml/README.md)
    * [Change key](reference/recipes/yaml/changekey.md)
    * [Change property key](reference/recipes/yaml/changepropertykey.md)
    * [Change value](reference/recipes/yaml/changevalue.md)
    * [Coalesce YAML properties](reference/recipes/yaml/coalesceproperties.md)
    * [Delete key](reference/recipes/yaml/deletekey.md)
    * [Delete property](reference/recipes/yaml/deleteproperty.md)
    * [Insert YAML snippet](reference/recipes/yaml/insertyaml.md)
    * [Cleanup](reference/recipes/yaml/cleanup/README.md)
      * [Remove unused YAML](reference/recipes/yaml/cleanup/removeunused.md)
    * [Format](reference/recipes/yaml/format/README.md)
      * [YAML indent](reference/recipes/yaml/format/indents.md)
    * [Search](reference/recipes/yaml/search/README.md)
      * [Find YAML entries](reference/recipes/yaml/search/findkey.md)