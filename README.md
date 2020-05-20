# Floyd算法
%% FileName:Floyd.m
%% Date:2020-4-13
%% Writer:YidaChen
%% Function:输出网络图的最短距离矩阵和路由矩阵，指定两结点间的最短距离及其路径

%%
function [D, P, dis, path] = Floyd(W, start, stop) %start为指定起始结点，stop为指定终止结点
