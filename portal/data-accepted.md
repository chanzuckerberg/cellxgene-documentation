# Accepted Data Types

Cellxgene is a repository of single cell data built to maximize data reuse. This page describes, at a high level, the data we can currently accept and the data we are working to accept in the future. 

<table>
  <thead>
    <tr>
      <th style="text-align:left">Characteristic</th>
      <th style="text-align:center">Accepted Now</th>
      <th style="text-align:center">Future</th>
      <th style="text-align:center">Never</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>DATA FORMAT</b>
      </td>
      <td style="text-align:center">AnnData Matrices of form (cell, gene) or (cell pool, gene)</td>
      <td style="text-align:center">Other feature types (see MEASUREMENT)</td>
      <td style="text-align:center">Raw data (fastq, bam, hybridization images)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>MEASUREMENT</b>
      </td>
      <td style="text-align:center">
        <p>Any assay that describes <em>gene</em> measurements</p>
        <p>Examples: scRNA-seq, scATAC-seq (gene activity), 10x Visium, patch-seq</p>
      </td>
      <td style="text-align:center">Protein and Splicing measurements</td>
      <td style="text-align:center"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>ORGANISM</b>
      </td>
      <td style="text-align:center">Human, Mouse, SARS-CoV2</td>
      <td style="text-align:center">Any organism with ENSEMBL gene annotations</td>
      <td style="text-align:center">Organisms lacking standard feature identifiers</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>DISEASE STATUS</b>
      </td>
      <td style="text-align:center">&gt; 20% of cells MUST be Healthy/Normal. Remaining may be from diseased
        samples</td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SAMPLE TYPE</b>
      </td>
      <td style="text-align:center">&gt; 50% of cells must be from tissue samples or organoids</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">Cell line datasets</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>OPEN SHARING</b>
      </td>
      <td style="text-align:center">Submitted data must be publicly accessible and contain no PII</td>
      <td
      style="text-align:center"></td>
        <td style="text-align:center">Controlled access data</td>
    </tr>
  </tbody>
</table>

A more detailed summary of cellxgene's requirements can be found in the [Cellxgene Data Integration Schema](https://github.com/chanzuckerberg/single-cell-curation/blob/main/schema/2.0.0/corpora_schema.md).

If you have data that match **all** of these characteristics, publishing it on the data portal can help amplify its reuse! 

