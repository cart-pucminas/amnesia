# Using Amnesia Simulator

This work has as main objective a study and approach of memory hierarchy learning using the Amnesia simulator. Different architectures will be presented in order to analyze the impact that changes can have in reducing cache miss and page fault. There are architectures and traces exploring spatial and temporal localities, made to verify if there has been an improvement or deterioration in the results, when fetching the instructions, when doing the exploration of the localities.

This work was carried out during the Computer Architecture III course in the Computer Science course at PUC Minas.

## Amnesia Simulator

Amnesia is a flexible simulator that allows users to assemble an architecture and trace it with the instructions that will run the way they want. The architecture is built in a file with an XML extension (Extensible Markup Language) and the trace in a file with extension txt(Text). Amnesia is an important tool for exploration of the memory hierarchy in computational systems because it allows simulating the behavior of memories cache, main memory and paged virtual memory. Since 2007, undergraduate and graduate students at the Institute of Mathematical and Computer Science (ICMC) at the University city of São Paulo (USP) develop Amnesia, oriented by professors Paulo Sérgio Lopes de Souza and Sarita Mazzini Bruschi.

## Creators
<ul>
    <li> [Cecilia Capurucho Bouchardet] (https://github.com/cecibou)</li>
    <li> [Danielle Dias Vieira] (https://github.com/DanielleDVieira)</li>
    <li> [João Augusto dos Santos Silva] (https://github.com/joaoaugustoss)</li>
    <li> [Thiago de Campos Ribeiro Nolasco] (https://github.com/Theeeccoo)</li>
</ul>

## Advisor
<ul>
	<li> [Henrique Cota de Freitas] (https://github.com/hcfreitas)</li>
</ul>

## Features
<ul>
    <li> Performance analysis when fetching instructions from cache memory and virtual memory.</li>
    <li> Visualization of time in milliseconds for executing instruction searches and number of misses and hits.</li>
    <li> Base architectures and with alterations that explore spatial and temporal localities.</li>
    <li> Three traces that search for instructions at random or that explore spatial and temporal localities.</li>
</ul>

## Installation
<ol>
    <li> JAVA 6.5 or higher.</li>
    <li> Clone the repository: `git clone https://github.com/cart-pucminas/amnesia`</li>
    <li> Download the cache memory and virtual memory modules to use the Amnesia simulator with the traces and architectures in this repository. Download from website: http://amnesia.lasdpc.icmc.usp.br/downloads/</li>
</ol>
<strong>Note:</strong> The traces and architectures in this repository need to be in the same folder as the simulators downloaded from the Amnesia website in order to be able to select the files.

## Usage

In these ZIP files of the modules downloaded from the Amnesia website, you will find the JAR file that runs Amnesia, architecture files (set up the memory hierarchy), trace files, folders with configuration files used during the run (do not remove these folders ), simulator usage tutorial (AmnesiaHelp folder).

<ol>
    <li> Open the Amnesia simulator in the module that you want to use the architectures and run the traces, either in cache memory or in virtual memory.</li>
    <li> Select the architecture you want to simulate and then the trace you want to run.</li>
    <li> Execute all instructions at once, or step by step through the simulator interface. When running a trace, its execution log is saved in the same folder as the architectures and traces used.</li>
</ol>

## References
<ul>
    <li> TIOSSO, F. ; Bruschi, S.M. ; SOUZA, P. S. L. ; BARBOSA, E. F. . Amnesia: um Objeto de Aprendizagem para o Ensino de Hierarquia de Memória, Proceedings of the 25o. Simpósio Brasileiro de Informática na Educação (SBIE 2014), Dourados, Sociedade Brasileira de Computação, 2014. v. 1. p. 1-10.</li>
    <li> Cacho, C. E. A. ; SOUZA, P. S. L. ; Bruschi, S.M. ; BARBOSA, E. F. ; TIOSSO, F.  An Interactive Approach for the Teaching of Virtual Memory Using Open Educational Resources. In: 31st ACM Symposium on Applied Computing – ACM SAC 2016, 2015, Pisa, Italy. Proceedings of ACM SAC 2016. New York : ACM, 2016. p. 225-231.     DOI: http://dx.doi.org/10.1145/2851613.2851700</li>
</ul>
