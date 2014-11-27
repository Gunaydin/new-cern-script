new-cern-script
===============

CERN script in C++

int nBins = 100
float xMin = 20
float xMax = 80
TH1F* myHisto = new TH1F("myHisto", "TITLE", nBins, xMin, xMax)
myHisto -> Fill(20)
myHisto -> Fill(20)
myHisto -> Fill(40)
myHisto -> Draw()
