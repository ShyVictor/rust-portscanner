<h1>Port Scanner</h1>

<p>Esta é uma ferramenta simples de scanner de portas escrita em Rust. Ela varre um host de destino e informa quais portas TCP estão abertas.</p>

<h2>Detalhes</h2>

<ul style="text-align: justify;">
<li>Possuí um bom modelo de E/S, a fim de evitar que o processo de varredura consuma todos os recursos do sistema. Além disso, a linguagem deve fornecer abstrações de alto nível e um sistema de empacotamento robusto, que permita isolar o código de baixo nível e reutilizá-lo facilmente em outros projetos.</li>

<li>Seguro em termos de tipos e memória, para evitar a criação de ferramentas ofensivas com vulnerabilidades que possam ser exploradas por atacantes. Essa segurança é uma vantagem importante do código desenvolvido, pois garante que a ferramenta seja confiável e possa ser usada com segurança em ambientes de produção.</li>

<li>Capacidade de suporte a concurrency e multithread é fundamental para um scanner de portas de alto desempenho. Uma linguagem que suporte essas funcionalidades pode realizar várias operações simultaneamente, reduzindo significativamente o tempo de execução do scanner de portas. Esse suporte à concurrency e multithread é outra grande vantagem do código que você desenvolveu, pois permite que o processo de varredura seja realizado de forma mais eficiente, com menos tempo de espera e mais rapidez na detecção das portas abertas.</li>
</ul>

<h2>Uso</h2>

<p>Para usar esta ferramenta, execute o arquivo principal com os seguintes argumentos:</p>

<pre>
$ cargo run &lt;target&gt; [--concurrency &lt;concurrency&gt;] [--verbose] [--full] [--timeout &lt;timeout&gt;]
</pre>

<p>A ferramenta irá então varrer o host de destino e informar quais portas TCP estão abertas dentro do intervalo especificado.</p>

<h2>Aviso</h2>

<p>Por favor, use esta ferramenta com responsabilidade e apenas com a permissão explícita do proprietário do host de destino. Qualquer uso indevido desta ferramenta é estritamente proibido e pode ser ilegal. O autor desta ferramenta não assume nenhuma responsabilidade por quaisquer danos ou consequências decorrentes do uso ou mau uso desta ferramenta.</p>
