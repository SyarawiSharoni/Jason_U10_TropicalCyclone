% Wind Speed (U10) estimates inside tropical cyclone environment
% JasonU10_ANN_TC.m
% Created by Syarawi Sharoni 4/11/2020
%
% This matlab scipt is to estimates U10 for Jason altimeter inside tropical cyclone environment
% Output, [y1] = Jason U10 wind speed.
% The input file in matrix form.
% Input, x1 = N x 9 matrix input parameters as listed below
% Column 1 = Ku-band backscatter
% Column 2 = C-band backscatter
% Column 3 = Ku-band SWH
% Column 4 = C-band SWH
% Column 5 = Brightness Temperature 18.7 GHz
% Column 6 = Brightness Temperature 23.8 GHz
% Column 7 = Brightness Temperature 34.0 GHz
% Column 8 = Liquid Water Content (LWC)
% Column 9 = Water Vapor Content (WVC)
%
% Detail paper discussed this model is "Tropical cyclone wind speed estimation from the satellite altimeter derived ocean parameters - Syarawi Sharoni,2021"
% Please cite the above paper. TQ. 
