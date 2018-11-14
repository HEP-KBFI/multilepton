# hh-multilepton
code and python config files for hh -> 4tau and hh->wwww analyses (all lepton and tau channels)

### Setup

```bash
git clone https://github.com/HEP-KBFI/hh-multilepton   $CMSSW_BASE/src/hhAnalysis/multilepton
git clone https://github.com/HEP-KBFI/tth-htt          $CMSSW_BASE/src/tthAnalysis/HiggsToTauTau
git clone https://github.com/SVfit/ClassicSVfit4tau    $CMSSW_BASE/src/TauAnalysis/ClassicSVfit4tau
git clone https://github.com/SVfit/ClassicSVfit        $CMSSW_BASE/src/TauAnalysis/ClassicSVfit
git clone https://github.com/SVfit/SVfitTF             $CMSSW_BASE/src/TauAnalysis/SVfitTF
curl -s https://raw.githubusercontent.com/cms-hh/HHStatAnalysis/master/install_ana_models.sh | bash -s (in $CMSSW_BASE/src/)
git clone https://github.com/cms-hh/Support.git        $CMSSW_BASE/src/Support
```
