---
layout: home
title: Download
subtitle: Download and Install RevBayes
permalink: /download
code_layout: bash
---
<h2>Command Line Interface</h2>
<div class="row">
<table class="table col-md-12">
    <thead>
        <tr>
            <th></th>
            <th style="text-align: center"><img src="{{ site.baseurl }}{% link assets/img/apple.png %}" alt="Apple" width="100px" /><h3>Mac OS X</h3></th>
            <th style="text-align: center"><img src="{{ site.baseurl }}{% link assets/img/windows.png %}" alt="Windows" width="100px" /><h3>Windows</h3></th>
            <th style="text-align: center"><img src="{{ site.baseurl }}{% link assets/img/tux.png %}" alt="Linux" width="100px" /><h3>Linux</h3></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">Download</th>
            <td style="text-align: center">
                <p><a href="https://github.com/revbayes/revbayes.archive/releases/download/v1.0.13/RevBayes_OSX_v1.0.13.zip" class="btn btn-info" role="button">Download Executable (10.6+)</a></p>
            </td>
            <td style="text-align: center">
                <p><a href="https://github.com/revbayes/revbayes.archive/releases/download/v1.0.13/RevBayes_Win_v1.0.13.zip" class="btn btn-info" role="button">Download Executable (10)</a></p>
            </td>
            <td style="text-align: center">
                <p><a href="https://github.com/revbayes/revbayes.archive/releases/download/v1.0.13/RevBayes_Singularity_v1.0.13.simg" class="btn btn-info" role="button">Download Singularity Image</a></p>
                <p><a href="{% page_url singularity %}">(Singularity notes)</a></p>
            </td>
        </tr>
        <tr>
            <th scope="row">Compile with <a href="https://spack.readthedocs.io/en/latest/">Spack</a></th>
            <td style="text-align: center">
                <p><a href="{% page_url compile_spack %}">Compile with Spack</a></p>
            </td>
            <td style="text-align: center">N/A</td>
            <td style="text-align: center">
                <p><a href="{% page_url compile_spack %}">Compile with Spack</a></p>
            </td>
        </tr>
        <tr>
            <th scope="row">Compile Manually</th>
            <td style="text-align: center"><p><a href="{% page_url compile_osx %}">OSX Compile Directions</a></p></td>
            <td style="text-align: center"><p><a href="{% page_url compile_windows %}">Windows Compile Directions</a></p></td>
            <td style="text-align: center"><p><a href="{% page_url compile_linux %}">Linux Compile Directions</a></p></td>
        </tr>
    </tbody>
</table>
</div>
<div class="row">
<div class="col-md-12">
<h2>Graphical Interface</h2>
<ul>
<li><a href="{% page_url gui_setup %}">Integration with Jupyter and RStudio</a></li>
</ul>
</div>
</div>