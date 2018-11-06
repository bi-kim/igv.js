# igv.js
[![Build Status](https://travis-ci.org/igvteam/igv.js.svg?branch=master)](https://travis-ci.org/igvteam/igv.js)

igv.js is an embeddable interactive genome visualization component developed by the 
 [Integrative Genomics Viewer (IGV)](https://igv.org) team.

 ```javascript
var options =
{
    genome: "hg19",
    locus: "chr8:128,747,267-128,754,546",
    theme: {
        bamTrackBgColor: "rgb(12,20,33)",
        featureTrackRectangleColor: "rgb(0,186,255)",
        featureTrackBgColor: "rgb(12,20,33)",
        featureTrackArrowColor: "rgb(255,255,255)",
        ideogramBgColor: "rgb(12,20,33)",
        rulerTrackLabelColor: "rgb(48,96,145)",
        rulerTrackTickColor: "rgb(48,96,145)",
        axisFontColor: "rgb(48,96,145)",
        axisBgColor: "rgb(12,20,33)"
    },
    tracks: [
        {
            type: 'alignment',
            format: 'bam',
            url: 'https://data.broadinstitute.org/igvdata/1KG/b37/data/HG02450/alignment/HG02450.mapped.ILLUMINA.bwa.ACB.low_coverage.20120522.bam',
            name: 'HG02450',
            color: "rgb(48,96,145)",
            coverageColor: "rgb(255,255,255)",
        }
    ]
};
 ```
  
## License

igv.js is [MIT](/LICENSE) licensed.

[documentation]: https://github.com/igvteam/igv.js/wiki
[examples]: http://igv.org/web/test/examples
