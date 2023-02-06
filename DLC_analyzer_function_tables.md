## Functions Glossary

Main functions, intended to be used by user:

  Function  | Description
  ------------- | -------------
  `AddBinData()`  | Adds bin data to an object of type TrackingData
  `AddLabelingData()`  | Adds labels to an object of type TrackingData
  `AddOFTZones()`|  Adds OFT zones to an object of type TackingData
  `AddPointInfo()` | Adds point info to an object of type Trackingdata
  `AddZones()` | Adds zones to an object of type TrackingData
  `AddZonesToPlots()` | Adds zones to a density path plot. Requires existing zones
  `BinAnalysis()` | Runs a analysis on an object of type TrackingData in bins. Requires existing bin data
  `CalculateAccelerations()` | Adds accelerations to an object of type TrackingData
  `CalculateMovement()` | Adds movement metrics to an object of type TrackingData
  `CalibrateTrackingData()` | Calibrates an object of Type TrackingData
  `ClassifyBehaviors()` | Classifies behaviors in an object of type TrackingData using a trained keras model. Requires existing trainings/testing data. REQUIRES KERAS LIBRARY!
  `CleanTrackingData()` | Cleanes up an object of type TrackingData
  `CombineLabels()` | Combines labels in an object of type TrackingData. Requires existing labels
  `CombineTrainingsData()` | Combines and prepares trainings data of multiple objects of type Trackingdata. Requires existing trainings data. REQUIRES KERAS LIBRARY!
  `CorrelationPlotLabels()` | Creates a correlation plot of different labels in a list of TrackingData objects. Requires existing labels
  `CreateAccelerationFeatures()` | Creates acceleration based features for an object of type TrackingData. Requires any DLC network of original publication. Requires existing acceleration data
  `CreateSkeletonData()` | Creates features based on skeleton data for an object of type TrackingData. Requires any DLC network of original publication
  `CreateSkeletonData_FST_v2()` | Creates features based on skeleton data for an object of type TrackingData. Requires FST DLC network from original publication. Requires existing acceleration data
  `CreateSkeletonData_OFT()` | Creates features based on skeleton data for an object of type TrackingData. Requires OFT DLC network from original publication. Requires existing OFT zones
  `CreateSkeletonData_OFT_v2()` | Creates features based on skeleton data for an object of type TrackingData. Requires OFT DLC network from original publication. Requires existing OFT zones. requires existing acceleration data
  `CreateSkeletonData_OFT_v3()` | Creates features based on skeleton data for an object of type TrackingData. Requires OFT DLC network from original publication. Requires existing OFT zones. Requires existing acceleration data
  `CreateTestSet()` | Adds machine learning test data for an object of type TrackingData. requires existing features
  `CreateTrainingSet()`|  Adds machine learning training data for an object of type Trackingdata. Requires existing features and labeling data.
`CutTrackingData()`|  Cuts an object of type TrackingData
`EPMAnalysis()`|  Performs a EPM analysis on an object of type TrackingData. requires EPM zones.
`EvaluateClassification()`|  Evaluates classification performance/accuracies of and object or a list of objects of type TrackingData
`ExtractLabels()`|  Extract labels from a long format data frame by multiple selection criterias
`FSTAnalysis()`|  Runs a FST analysis on an object of type TrackingData. Requires 
`GetAngleClockwise()`|  Gets the clock wise angle between a vector pair from an object of type TrackingData at each frame
`GetAngleTotal()`|  Gets the total angle between two vectors from an object of type TrackingData at each frame
`GetDistances()`|  Gets the distance between two points from an object of type TrackingData at each frame
`GetDistanceToZoneBorder()`|  Gets the distance between a point an the border of a zone from an object of type TrackingData at each frame
`GetPolygonAreas()`|  Gets area of a polygon from an object of type TrackingData at each frame
`HeadAngleAnalysis()`|  Performs a head angle analysis for an object of type TrackingData
`IsInZone()`|  Checks if a point is in a zone  for an object of type TrackingData at each frame
`IsTrackingData()`|  Checks if object is of type TrackingData
`LabelReport()`|  Creates a Label report for an object of type TrackingData. requires labels.
`MedianMouseArea()`|  Calculates the median mouse area for an object of type TrackingData
`MedianMouseLength()`|  Calculates the median mouse length for an object of type TrackingData
`MultiFileBinanalysis()`|  Performs a bin analysis for a list() of files of type TrackingData. requires bin data.
`MultiFileReport()`|  Produces a combined report for a list() of files of type TrackingData.
`NormalizeZscore()`|  Performs a Z score normalization on a matrix by columns
`NormalizeZscore_median()`|  Performs a median Z score normalization on a matrix by columns
`OFTAnalysis()`|  Performs a OFT analysis on an object of type TrackingData. requires OFT zones.
`OverviewPlot()`|  Creates an overview plot for an object of type TrackingData
`PlotDensityPaths()`|  For an object of type TrackingData, plots the density path of a point
`PlotDensityPaths.Multi.PDF()`|  For a list() of objects of type TrackingData. Prints density path plots to a pdf.
`PlotLabels()`|  For an object of type TrackingData, plots label data 
`PlotLabels.Multi.PDF()`|  For a list() of objects of type TrackingData. Prints label plots to a pdf. 
`PlotPointData()`|  Plots point data for an object of type TrackingData. 
`PlotZones()`|  Plots zones of an object of type TrackingData. requires zones
`PlotZoneSelection()`|  Plots the zone selection for an object of type TrackingData. requires zones
`PlotZoneVisits()`|  Plots zone visits for an object of type TrackingData. requires zones 
`PlotZoneVisits.Multi.PDF()`|  For a list() of objects of type TrackingData. Prints zone visit plots to a pdf. requires zones  
`PrepareMLData()`|  Prepares x_train and y_train data for a keras network. REQUIRES KERAS LIBRARY!
`ReadDLCDataFromCSV()`|  Creates an object of type TrackingData from a DLC .csv output file
`RotateTrackingData()`|  Rotates an object of type TrackingData 
`RunPipeline()`|  Runs a specified pipeline that loads and processes multiple objects of type TrackingData
`ScaleFeatures()`|  Linerly scales feature data of an object of type TrackingData. requries feature data. 
`SmoothLabels()`|  Smooths all labeling data of an object of type TrackingData. requires labels
`UnsupervisedClusteringKmeans()`|  Performs a k means clustering on an object (or list() of objects) of type TrackingData 
`ZoneReport()`|  Creates a zone report for an object of type TrackingData 
`ZscoreNormalizeFeatures()`|  Performs Z score normalization on features of an object of type TrackingData. Requires Features

Auxiliary functions:

  Function  | Description
  ------------- | -------------
`AreaPolygon2d()` | Calculates the area of a polygon
`AreaPolygon3d()` | Calculates the area of a polygon at each frame
`avgbool()` | Logical rolling mean of a boolean vector
`avgmean()` | Numeric rolling mean of a numeric vector
`CalculateTransitions()` | Calculates transitions for a boolean vector
`Distance2d()`|  Distance between two points
`DistanceToPolygon()`|  Distance from a point to the closest polygon edge
`EqualizeTrainingSet()`|  Equalizes a training set
`integratevector()`|  integration of a numeric vector
`periodsum()`|  For a numeric vector, sums up total values within a time period at each element
`RecenterPolygon()`|  Recenters a polygon 
`ScalePolygon()`|  Linearly scales a polygon 
`SmoothLabel()`| Smooths a single character vector with label data