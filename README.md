
            
  <div class="section" id="full-pytest-documentation">
<span id="toc"></span><h1>Full pytest documentation<a class="headerlink" href="#full-pytest-documentation" title="Permalink to this headline">¶</a></h1>
<p><a class="reference external" href="https://media.readthedocs.org/pdf/pytest/latest/pytest.pdf">Download latest version as PDF</a></p>
<div class="section" id="start-here">
<h2>Start here<a class="headerlink" href="#start-here" title="Permalink to this headline">¶</a></h2>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="getting-started.html">Get Started</a><ul>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#install-pytest">Install <code class="docutils literal notranslate"><span class="pre">pytest</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#create-your-first-test">Create your first test</a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#run-multiple-tests">Run multiple tests</a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#assert-that-a-certain-exception-is-raised">Assert that a certain exception is raised</a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#group-multiple-tests-in-a-class">Group multiple tests in a class</a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#request-a-unique-temporary-directory-for-functional-tests">Request a unique temporary directory for functional tests</a></li>
<li class="toctree-l2"><a class="reference internal" href="getting-started.html#continue-reading">Continue reading</a></li>
</ul>
</li>
</ul>
</div>
</div>
<div class="section" id="how-to-guides">
<h2>How-to guides<a class="headerlink" href="#how-to-guides" title="Permalink to this headline">¶</a></h2>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="how-to/usage.html">How to invoke pytest</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/usage.html#specifying-which-tests-to-run">Specifying which tests to run</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/usage.html#getting-help-on-version-option-names-environment-variables">Getting help on version, option names, environment variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/usage.html#profiling-test-execution-duration">Profiling test execution duration</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/usage.html#managing-loading-of-plugins">Managing loading of plugins</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/usage.html#other-ways-of-calling-pytest">Other ways of calling pytest</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/assert.html">How to write and report assertions in tests</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#asserting-with-the-assert-statement">Asserting with the <code class="docutils literal notranslate"><span class="pre">assert</span></code> statement</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#assertions-about-expected-exceptions">Assertions about expected exceptions</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#assertions-about-expected-warnings">Assertions about expected warnings</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#making-use-of-context-sensitive-comparisons">Making use of context-sensitive comparisons</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#defining-your-own-explanation-for-failed-assertions">Defining your own explanation for failed assertions</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/assert.html#assertion-introspection-details">Assertion introspection details</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/fixtures.html">How to use fixtures</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#requesting-fixtures">“Requesting” fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#autouse-fixtures-fixtures-you-don-t-have-to-request">Autouse fixtures (fixtures you don’t have to request)</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#scope-sharing-fixtures-across-classes-modules-packages-or-session">Scope: sharing fixtures across classes, modules, packages or session</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#teardown-cleanup-aka-fixture-finalization">Teardown/Cleanup (AKA Fixture finalization)</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#safe-teardowns">Safe teardowns</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#running-multiple-assert-statements-safely">Running multiple <code class="docutils literal notranslate"><span class="pre">assert</span></code> statements safely</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#fixtures-can-introspect-the-requesting-test-context">Fixtures can introspect the requesting test context</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#using-markers-to-pass-data-to-fixtures">Using markers to pass data to fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#factories-as-fixtures">Factories as fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#parametrizing-fixtures">Parametrizing fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#using-marks-with-parametrized-fixtures">Using marks with parametrized fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#modularity-using-fixtures-from-a-fixture-function">Modularity: using fixtures from a fixture function</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#automatic-grouping-of-tests-by-fixture-instances">Automatic grouping of tests by fixture instances</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#use-fixtures-in-classes-and-modules-with-usefixtures">Use fixtures in classes and modules with <code class="docutils literal notranslate"><span class="pre">usefixtures</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#overriding-fixtures-on-various-levels">Overriding fixtures on various levels</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/fixtures.html#using-fixtures-from-other-projects">Using fixtures from other projects</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/mark.html">How to mark test functions with attributes</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/mark.html#registering-marks">Registering marks</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/mark.html#raising-errors-on-unknown-marks">Raising errors on unknown marks</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/parametrize.html">How to parametrize fixtures and test functions</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/parametrize.html#pytest-mark-parametrize-parametrizing-test-functions"><code class="docutils literal notranslate"><span class="pre">&#64;pytest.mark.parametrize</span></code>: parametrizing test functions</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/parametrize.html#basic-pytest-generate-tests-example">Basic <code class="docutils literal notranslate"><span class="pre">pytest_generate_tests</span></code> example</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/parametrize.html#more-examples">More examples</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/tmp_path.html">How to use temporary directories and files in tests</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/tmp_path.html#the-tmp-path-fixture">The <code class="docutils literal notranslate"><span class="pre">tmp_path</span></code> fixture</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/tmp_path.html#the-tmp-path-factory-fixture">The <code class="docutils literal notranslate"><span class="pre">tmp_path_factory</span></code> fixture</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/tmp_path.html#the-tmpdir-and-tmpdir-factory-fixtures">The <code class="docutils literal notranslate"><span class="pre">tmpdir</span></code> and <code class="docutils literal notranslate"><span class="pre">tmpdir_factory</span></code> fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/tmp_path.html#the-default-base-temporary-directory">The default base temporary directory</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/monkeypatch.html">How to monkeypatch/mock modules and environments</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#monkeypatching-functions">Monkeypatching functions</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#monkeypatching-returned-objects-building-mock-classes">Monkeypatching returned objects: building mock classes</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#global-patch-example-preventing-requests-from-remote-operations">Global patch example: preventing “requests” from remote operations</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#monkeypatching-environment-variables">Monkeypatching environment variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#monkeypatching-dictionaries">Monkeypatching dictionaries</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/monkeypatch.html#api-reference">API Reference</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/doctest.html">How to run doctests</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#encoding">Encoding</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#using-doctest-options">Using ‘doctest’ options</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#continue-on-failure">Continue on failure</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#output-format">Output format</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#pytest-specific-features">pytest-specific features</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/doctest.html#alternatives">Alternatives</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/cache.html">How to re-run failed tests and maintain state between test runs</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#usage">Usage</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#rerunning-only-failures-or-failures-first">Rerunning only failures or failures first</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#behavior-when-no-tests-failed-in-the-last-run">Behavior when no tests failed in the last run</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#the-new-config-cache-object">The new config.cache object</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#inspecting-cache-content">Inspecting Cache content</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#clearing-cache-content">Clearing Cache content</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/cache.html#stepwise">Stepwise</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/logging.html">How to manage logging</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/logging.html#caplog-fixture">caplog fixture</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/logging.html#live-logs">Live Logs</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/logging.html#customizing-colors">Customizing Colors</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/logging.html#release-notes">Release notes</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/logging.html#incompatible-changes-in-pytest-3-4">Incompatible changes in pytest 3.4</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/capture-stdout-stderr.html">How to capture stdout/stderr output</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-stdout-stderr.html#default-stdout-stderr-stdin-capturing-behaviour">Default stdout/stderr/stdin capturing behaviour</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-stdout-stderr.html#setting-capturing-methods-or-disabling-capturing">Setting capturing methods or disabling capturing</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-stdout-stderr.html#using-print-statements-for-debugging">Using print statements for debugging</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-stdout-stderr.html#accessing-captured-output-from-a-test-function">Accessing captured output from a test function</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/capture-warnings.html">How to capture warnings</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#controlling-warnings">Controlling warnings</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#pytest-mark-filterwarnings"><code class="docutils literal notranslate"><span class="pre">&#64;pytest.mark.filterwarnings</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#disabling-warnings-summary">Disabling warnings summary</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#disabling-warning-capture-entirely">Disabling warning capture entirely</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#deprecationwarning-and-pendingdeprecationwarning">DeprecationWarning and PendingDeprecationWarning</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#ensuring-code-triggers-a-deprecation-warning">Ensuring code triggers a deprecation warning</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#warns">Asserting warnings with the warns function</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#recwarn">Recording warnings</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#additional-use-cases-of-warnings-in-tests">Additional use cases of warnings in tests</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#custom-failure-messages">Custom failure messages</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#internal-pytest-warnings">Internal pytest warnings</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/capture-warnings.html#resource-warnings">Resource Warnings</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/skipping.html">How to use skip and xfail to deal with tests that cannot succeed</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/skipping.html#skipping-test-functions">Skipping test functions</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/skipping.html#xfail-mark-test-functions-as-expected-to-fail">XFail: mark test functions as expected to fail</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/skipping.html#skip-xfail-with-parametrize">Skip/xfail with parametrize</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/plugins.html">How to install and use plugins</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/plugins.html#requiring-loading-plugins-in-a-test-module-or-conftest-file">Requiring/Loading plugins in a test module or conftest file</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/plugins.html#finding-out-which-plugins-are-active">Finding out which plugins are active</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/plugins.html#deactivating-unregistering-a-plugin-by-name">Deactivating / unregistering a plugin by name</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/writing_plugins.html">Writing plugins</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#plugin-discovery-order-at-tool-startup">Plugin discovery order at tool startup</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#conftest-py-local-per-directory-plugins">conftest.py: local per-directory plugins</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#writing-your-own-plugin">Writing your own plugin</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#making-your-plugin-installable-by-others">Making your plugin installable by others</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#assertion-rewriting">Assertion Rewriting</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#requiring-loading-plugins-in-a-test-module-or-conftest-file">Requiring/Loading plugins in a test module or conftest file</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#accessing-another-plugin-by-name">Accessing another plugin by name</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#registering-custom-markers">Registering custom markers</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_plugins.html#testing-plugins">Testing plugins</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/writing_hook_functions.html">Writing hook functions</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#hook-function-validation-and-execution">hook function validation and execution</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#firstresult-stop-at-first-non-none-result">firstresult: stop at first non-None result</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#hookwrapper-executing-around-other-hooks">hookwrapper: executing around other hooks</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#hook-function-ordering-call-example">Hook function ordering / call example</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#declaring-new-hooks">Declaring new hooks</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#using-hooks-in-pytest-addoption">Using hooks in pytest_addoption</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#optionally-using-hooks-from-3rd-party-plugins">Optionally using hooks from 3rd party plugins</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/writing_hook_functions.html#storing-data-on-items-across-hook-functions">Storing data on items across hook functions</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/existingtestsuite.html">How to use pytest with an existing test suite</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/existingtestsuite.html#running-an-existing-test-suite-with-pytest">Running an existing test suite with pytest</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/unittest.html">How to use <code class="docutils literal notranslate"><span class="pre">unittest</span></code>-based tests with pytest</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/unittest.html#benefits-out-of-the-box">Benefits out of the box</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/unittest.html#pytest-features-in-unittest-testcase-subclasses">pytest features in <code class="docutils literal notranslate"><span class="pre">unittest.TestCase</span></code> subclasses</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/unittest.html#mixing-pytest-fixtures-into-unittest-testcase-subclasses-using-marks">Mixing pytest fixtures into <code class="docutils literal notranslate"><span class="pre">unittest.TestCase</span></code> subclasses using marks</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/unittest.html#using-autouse-fixtures-and-accessing-other-fixtures">Using autouse fixtures and accessing other fixtures</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/nose.html">How to run tests written for nose</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/nose.html#usage">Usage</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/nose.html#supported-nose-idioms">Supported nose Idioms</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/nose.html#unsupported-idioms-known-issues">Unsupported idioms / known issues</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/nose.html#migrating-from-nose-to-pytest">Migrating from nose to pytest</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/xunit_setup.html">How to implement xunit-style set-up</a><ul>
<li class="toctree-l2"><a class="reference internal" href="how-to/xunit_setup.html#module-level-setup-teardown">Module level setup/teardown</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/xunit_setup.html#class-level-setup-teardown">Class level setup/teardown</a></li>
<li class="toctree-l2"><a class="reference internal" href="how-to/xunit_setup.html#method-and-function-level-setup-teardown">Method and function level setup/teardown</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="how-to/bash-completion.html">How to set up bash completion</a></li>
</ul>
</div>
</div>
<div class="section" id="reference-guides">
<h2>Reference guides<a class="headerlink" href="#reference-guides" title="Permalink to this headline">¶</a></h2>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="reference/fixtures.html">Fixtures reference</a><ul>
<li class="toctree-l2"><a class="reference internal" href="reference/fixtures.html#built-in-fixtures">Built-in fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/fixtures.html#fixture-availability">Fixture availability</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/fixtures.html#fixture-instantiation-order">Fixture instantiation order</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="reference/plugin_list.html">Plugin List</a></li>
<li class="toctree-l1"><a class="reference internal" href="reference/customize.html">Configuration</a><ul>
<li class="toctree-l2"><a class="reference internal" href="reference/customize.html#command-line-options-and-configuration-file-settings">Command line options and configuration file settings</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/customize.html#configuration-file-formats">Configuration file formats</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/customize.html#initialization-determining-rootdir-and-configfile">Initialization: determining rootdir and configfile</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/customize.html#builtin-configuration-file-options">Builtin configuration file options</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/customize.html#syntax-highlighting-theme-customization">Syntax highlighting theme customization</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="reference/reference.html">API Reference</a><ul>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#constants">Constants</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#functions">Functions</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#marks">Marks</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#fixtures">Fixtures</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#hooks">Hooks</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#objects">Objects</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#global-variables">Global Variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#environment-variables">Environment Variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#exceptions">Exceptions</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#warnings">Warnings</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#configuration-options">Configuration Options</a></li>
<li class="toctree-l2"><a class="reference internal" href="reference/reference.html#command-line-flags">Command-line Flags</a></li>
</ul>
</li>
</ul>
</div>
</div>
<div class="section" id="explanation">
<h2>Explanation<a class="headerlink" href="#explanation" title="Permalink to this headline">¶</a></h2>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="explanation/anatomy.html">Anatomy of a test</a></li>
<li class="toctree-l1"><a class="reference internal" href="explanation/fixtures.html">About fixtures</a><ul>
<li class="toctree-l2"><a class="reference internal" href="explanation/fixtures.html#what-fixtures-are">What fixtures are</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/fixtures.html#improvements-over-xunit-style-setup-teardown-functions">Improvements over xUnit-style setup/teardown functions</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/fixtures.html#fixture-errors">Fixture errors</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/fixtures.html#sharing-test-data">Sharing test data</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/fixtures.html#a-note-about-fixture-cleanup">A note about fixture cleanup</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="explanation/goodpractices.html">Good Integration Practices</a><ul>
<li class="toctree-l2"><a class="reference internal" href="explanation/goodpractices.html#install-package-with-pip">Install package with pip</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/goodpractices.html#conventions-for-python-test-discovery">Conventions for Python test discovery</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/goodpractices.html#choosing-a-test-layout-import-rules">Choosing a test layout / import rules</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/goodpractices.html#tox">tox</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/goodpractices.html#do-not-run-via-setuptools">Do not run via setuptools</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="explanation/flaky.html">Flaky tests</a><ul>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#why-flaky-tests-are-a-problem">Why flaky tests are a problem</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#potential-root-causes">Potential root causes</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#pytest-features">Pytest features</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#other-general-strategies">Other general strategies</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#research">Research</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/flaky.html#resources">Resources</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="explanation/pythonpath.html">pytest import mechanisms and <code class="docutils literal notranslate"><span class="pre">sys.path</span></code>/<code class="docutils literal notranslate"><span class="pre">PYTHONPATH</span></code></a><ul>
<li class="toctree-l2"><a class="reference internal" href="explanation/pythonpath.html#import-modes">Import modes</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/pythonpath.html#prepend-and-append-import-modes-scenarios"><code class="docutils literal notranslate"><span class="pre">prepend</span></code> and <code class="docutils literal notranslate"><span class="pre">append</span></code> import modes scenarios</a></li>
<li class="toctree-l2"><a class="reference internal" href="explanation/pythonpath.html#invoking-pytest-versus-python-m-pytest">Invoking <code class="docutils literal notranslate"><span class="pre">pytest</span></code> versus <code class="docutils literal notranslate"><span class="pre">python</span> <span class="pre">-m</span> <span class="pre">pytest</span></code></a></li>
</ul>
</li>
</ul>
</div>
</div>
<div class="section" id="further-topics">
<h2>Further topics<a class="headerlink" href="#further-topics" title="Permalink to this headline">¶</a></h2>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="example/index.html">Examples and customization tricks</a><ul>
<li class="toctree-l2"><a class="reference internal" href="example/reportingdemo.html">Demo of Python failure reports with pytest</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/simple.html">Basic patterns and examples</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/parametrize.html">Parametrizing tests</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/markers.html">Working with custom markers</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/special.html">A session-fixture which can look at all collected tests</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/pythoncollection.html">Changing standard (Python) test discovery</a></li>
<li class="toctree-l2"><a class="reference internal" href="example/nonpython.html">Working with non-python tests</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="backwards-compatibility.html">Backwards Compatibility Policy</a></li>
<li class="toctree-l1"><a class="reference internal" href="backwards-compatibility.html#history">History</a><ul>
<li class="toctree-l2"><a class="reference internal" href="backwards-compatibility.html#focus-primary-on-smooth-transition-stance-pre-6-0">Focus primary on smooth transition - stance (pre 6.0)</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="backwards-compatibility.html#python-version-support">Python version support</a></li>
<li class="toctree-l1"><a class="reference internal" href="deprecations.html">Deprecations and Removals</a><ul>
<li class="toctree-l2"><a class="reference internal" href="deprecations.html#deprecated-features">Deprecated Features</a></li>
<li class="toctree-l2"><a class="reference internal" href="deprecations.html#removed-features">Removed Features</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="contributing.html">Contribution getting started</a><ul>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#feature-requests-and-feedback">Feature requests and feedback</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#report-bugs">Report bugs</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#fix-bugs">Fix bugs</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#implement-features">Implement features</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#write-documentation">Write documentation</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#submitting-plugins-to-pytest-dev">Submitting Plugins to pytest-dev</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#preparing-pull-requests">Preparing Pull Requests</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#joining-the-development-team">Joining the Development Team</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#backporting-bug-fixes-for-the-next-patch-release">Backporting bug fixes for the next patch release</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#handling-stale-issues-prs">Handling stale issues/PRs</a></li>
<li class="toctree-l2"><a class="reference internal" href="contributing.html#closing-issues">Closing Issues</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="development_guide.html">Development Guide</a></li>
<li class="toctree-l1"><a class="reference internal" href="sponsor.html">Sponsor</a><ul>
<li class="toctree-l2"><a class="reference internal" href="sponsor.html#opencollective">OpenCollective</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="tidelift.html">pytest for enterprise</a></li>
<li class="toctree-l1"><a class="reference internal" href="license.html">License</a></li>
<li class="toctree-l1"><a class="reference internal" href="contact.html">Contact channels</a></li>
<li class="toctree-l1"><a class="reference internal" href="history.html">History</a></li>
<li class="toctree-l1"><a class="reference internal" href="historical-notes.html">Historical Notes</a><ul>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#marker-revamp-and-iteration">Marker revamp and iteration</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#cache-plugin-integrated-into-the-core">cache plugin integrated into the core</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#funcargs-and-pytest-funcarg">funcargs and <code class="docutils literal notranslate"><span class="pre">pytest_funcarg__</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#pytest-yield-fixture-decorator"><code class="docutils literal notranslate"><span class="pre">&#64;pytest.yield_fixture</span></code> decorator</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#pytest-header-in-setup-cfg"><code class="docutils literal notranslate"><span class="pre">[pytest]</span></code> header in <code class="docutils literal notranslate"><span class="pre">setup.cfg</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#applying-marks-to-pytest-mark-parametrize-parameters">Applying marks to <code class="docutils literal notranslate"><span class="pre">&#64;pytest.mark.parametrize</span></code> parameters</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#pytest-mark-parametrize-argument-names-as-a-tuple"><code class="docutils literal notranslate"><span class="pre">&#64;pytest.mark.parametrize</span></code> argument names as a tuple</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#setup-is-now-an-autouse-fixture">setup: is now an “autouse fixture”</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#conditions-as-strings-instead-of-booleans">Conditions as strings instead of booleans</a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#pytest-set-trace"><code class="docutils literal notranslate"><span class="pre">pytest.set_trace()</span></code></a></li>
<li class="toctree-l2"><a class="reference internal" href="historical-notes.html#compat-properties">“compat” properties</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="talks.html">Talks and Tutorials</a><ul>
<li class="toctree-l2"><a class="reference internal" href="talks.html#books">Books</a></li>
<li class="toctree-l2"><a class="reference internal" href="talks.html#talks-and-blog-postings">Talks and blog postings</a></li>
</ul>
</li>
</ul>
</div>
<div class="toctree-wrapper compound">
<ul>
<li class="toctree-l1"><a class="reference internal" href="announce/index.html">Release announcements</a></li>
</ul>
</div>
<div class="toctree-wrapper compound">
</div>
</div>
</div>
  

<div id="searchbox" style="display: none" role="search">
  <div class="searchformwrapper">
    <form class="search" action="search.html" method="get">
      <input type="text" name="q" aria-labelledby="searchlabel"
        placeholder="Search"/>
      <input type="submit" value="Go" />
    </form>
  </div>
</div>

<ul>
  <li><a href="index.html">Home</a></li>

  <li><a href="getting-started.html">Get started</a></li>
  <li><a href="how-to/index.html">How-to guides</a></li>
  <li><a href="reference/index.html">Reference guides</a></li>
  <li><a href="explanation/index.html">Explanation</a></li>
  <li><a href="#">Complete table of contents</a></li>
  <li><a href="example/index.html">Library of examples</a></li>
</ul>

<h3>About the project</h3>

<ul>
  <li><a href="changelog.html">Changelog</a></li>
  <li><a href="contributing.html">Contributing</a></li>
  <li><a href="backwards-compatibility.html">Backwards Compatibility</a></li>
  <li><a href="sponsor.html">Sponsor</a></li>
  <li><a href="tidelift.html">pytest for Enterprise</a></li>
  <li><a href="license.html">License</a></li>
  <li><a href="contact.html">Contact Channels</a></li>
</ul>
  <hr>
  <ul>
<li><a class="reference internal" href="#">Full pytest documentation</a><ul>
<li><a class="reference internal" href="#start-here">Start here</a></li>
<li><a class="reference internal" href="#how-to-guides">How-to guides</a></li>
<li><a class="reference internal" href="#reference-guides">Reference guides</a></li>
<li><a class="reference internal" href="#explanation">Explanation</a></li>
<li><a class="reference internal" href="#further-topics">Further topics</a><ul>
</ul>
</li>
</ul>
</li>
</ul>


<hr><h3>Related Topics</h3>
<ul>
  <li><a href="#">Documentation overview</a><ul>
      <li>Next: <a href="getting-started.html" title="next chapter">Get Started</a></li>
  </ul></li>
</ul><h3>Useful Links</h3>
<ul>
  <li><a href="https://pypi.org/project/pytest/">pytest @ PyPI</a></li>
  <li><a href="https://github.com/pytest-dev/pytest/">pytest @ GitHub</a></li>
  <li><a href="https://github.com/pytest-dev/pytest/issues">Issue Tracker</a></li>
  <li><a href="https://media.readthedocs.org/pdf/pytest/latest/pytest.pdf">PDF Documentation</a>
</ul>
        </div>
      </div>
      <div class="clearer"></div>
    </div>
 

  </body>
</html>
