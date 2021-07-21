---


---

<p>Code base structure<br>
PHPSandbox cli is built using <a href="https://laravel-zero.com">laravel zero</a> and this makes it very easy for anyone coming from a <a href="laravel.com">laravel</a> background to get to contributing straight away.</p>
<ol>
<li>The app directory contains the application logic and it is where all classes are expected to be placed.</li>
<li>app/Services directory is where Service classes are placed.  Ideally complex tasks are not expected to be completely run in the console classes. Service classes are created so the console classes primary handle input and output.</li>
<li>app/Traits directory is where all traits are placed.</li>
<li>app/Contracts directory is where interfaces are placed.</li>
<li>app/Commands is where all console classes are placed.</li>
<li>app/Exceptions is where all exception classes are placed.</li>
<li>app/Http contains the Client class.</li>
<li>The config directory contains all configuration files and more can be added only if required.</li>
</ol>

