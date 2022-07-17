<H4>Vault Build Templates</H4>
<p> Set of MS Build Property & Target files to make upating Vault addins for mutiple releases easier.</p>

<H4>Usage</H4>
<p>
  
  Include the following in the Main Project File, <i>or any sub project referencing Vault SDK</i>
<ol>
  <li><code>&ltImport Project="$(SolutionDir)BuildConfigs\BuildConfigurations.properties" /&gt</code></li>
  <li><code>&ltImport Project="$(SolutionDir)BuildConfigs\BuildStandard.properties" /&gt</code></li>
  <li><code>&ltImport Project="$(SolutionDir)BuildConfigs\VaultProperties.properties" /&gt</code></li>
</ol>
  
  Include the following in the Main Project File <b>only</b>
<ol>
  <li><code>&ltImport Project="$(SolutionDir)BuildConfigs\VaultBuild.targets" &gt</code></li>
  
</ol>
  </p>
