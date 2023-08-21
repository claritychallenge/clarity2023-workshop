---
layout: page
title: Results
---

<div class="panel panel-default">
<div class="panel-body">

<div class="bg-light py-1">
      <div class="container page-content">
          <article>

Results are shown for all submitted systems. For RMSE scores, small values are best. For correlation coefficients (corr), large numbers are best. The table also identifies which systems are intrusive and which are non-intrusive. The system labeled 'prior' simply returns the training set average sentence intelligibility for all sentences. The beHASPI system is the baseline supplied by the organisers.

<table
  class="datatable table table-hover table-condensed"
  data-bar-hline="true"
  data-chart-default-mode="bar"
  data-chart-modes="bar,scatter"
  data-id-field="name"
  data-pagination="false"
  data-rank-mode="grouped_muted"
  data-row-highlighting="true"
  data-bar-height="340"
  data-show-chart="true"
  data-show-rank="true"
  data-sort-name="closed_rmse"
  data-sort-order="inc"
  data-scatter-x="closed_rmse"
  data-scatter-y="open_rmse"
  data-line-yaxis-beginatzero="true"
>
  <thead>
    <tr>
      <th class="sep-left-cell text-center" data-rank="true">Rank</th>
      <th
        class="sep-left-cell text-center"
        data-field="name"
        data-sortable="true"
        data-value-type="str"
        id="team"
      >
        Team
      </th>
      <th
        class="sep-left-cell text-center"
        data-field="paper"
        data-sortable="true"
        data-value-type="str"
        id="team"
      >
        Paper
      </th>
       <th
        class="sep-left-cell text-center"
        data-chartable="true"
        data-field="intrusive"
        data-sortable="true"
        data-value-type="bool"
        id="intrusive"
      >
        Intrusive?
      </th>
      <th
        class="sep-left-cell text-center"
        data-chartable="true"
        data-field="closed_rmse"
        data-sortable="true"
        data-value-type="float1"
      >
        RMSE
      </th>
      <th
        class="sep-right-cell sep-left-cell text-center"
        data-chartable="true"
        data-field="closed_corr"
        data-sortable="true"
        data-value-type="float2"
      >
        Corr
      </th>

    </tr>
  </thead>

  <tbody>

    <tr>
      <td></td>
      <td>E011</td>
      <td>
        <a
          href="./papers/CPC2_E011_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>25.1</td>
      <td>0.78</td>
    </tr>

 <tr>
      <td></td>
      <td>E002</td>
      <td>
<a
          href="./papers/CPC2_E002_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>25.3</td>
      <td>0.77</td>
    </tr>

    <tr>
      <td></td>
      <td>E009</td>
      <td>
        <a
          href="./papers/CPC2_E009_report.pdf"
          >[paper]</a
        >
      </td>
      <td>Yes</td>
      <td>25.4</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E022</td>
      <td>
        <a
          href="./papers/CPC2_E022_report.pdf"
          >[paper]</a
        >
      </td>
      <td>Yes</td>
      <td>25.7</td>
      <td>0.77</td>
    </tr>

    <tr>
      <td></td>
      <td>E023</td>
      <td>
        <a
          href="./papers/CPC2_E023_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>26.4</td>
      <td>0.76</td>
    </tr>
    
    <tr>
      <td></td>
      <td>E016</td>
      <td>
        <a
          href="./papers/CPC2_E016_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>26.8</td>
      <td>0.75</td>
    </tr>

    <tr>
      <td></td>
      <td>E025</td>
      <td>
        <a
          href="./papers/CPC2_E025_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>27.9</td>
      <td>0.72</td>
    </tr>
    
    <tr>
      <td></td>
      <td>beHASPI</td>
      <td>
      
      </td>
      <td>Yes</td>
      <td>28.7</td>
      <td>0.70</td>
    </tr>

    <tr>
      <td></td>
      <td>E003</td>
      <td>
        <a
          href="./papers/CPC2_E003_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>31.1</td>
      <td>0.64</td>
    </tr>
    
    <tr>
      <td></td>
      <td>E024</td>
      <td>
        <a
          href="./papers/CPC2_E024_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>31.7</td>
      <td>0.62</td>
    </tr>

    <tr>
      <td></td>
      <td>E015</td>
      <td>
        <a
          href="./papers/CPC2_E015_report.pdf"
          >[paper]</a
        >
      </td>
      <td>No</td>
      <td>35.0</td>
      <td>0.60</td>
    </tr>
    
    <!--
    <tr>
      <td></td>
      <td>E019</td>
      <td>
        
      </td>
      <td>No</td>
      <td></td>
      <td></td>
    </tr>
 -->
    <tr>
      <td></td>
      <td>E020</td>
      <td>

      </td>
      <td>No</td>
      <td>39.8</td>
      <td>0.33</td>
    </tr>
    
    <tr>
      <td></td>
      <td>Prior</td>
      <td>
        
      </td>
      <td>No</td>
      <td>40.0</td>
      <td>-</td>
    </tr>

  </tbody>
</table>

<header>
    <h1>Prizes</h1>
  </header>

  <section>
    <br />

<p>The Hearing Industry Research Consortium best system prizes were awarded to</p>

<ul>
<li> 1st place: Cuervo and Marxer, <strong>Temporal-heirarchical features from noise-robust speech foundation models for non-intrusive intelligibility prediction</strong> for best performance overall performance,</li>
<li> 2nd place: Mogridge et al., <strong>Pre-training intermediate ASR features and Human memory simulation for non-intrusive speech intelligibility prediction in the Clarity Prediction Challenge 2</strong> for 2nd best overall score.</li>
</ul>

(Note, although 1st and 2nd place systems had very similar RMSE scores, a paired t-test showed that the difference was highly significant).

<p/>

<p>Congratulations to the winners!</p>

<br />
<a href="#TOP">[TOP]</a>
<p />
<br />
<br />

  </section>

</article>

</div>

</div>
