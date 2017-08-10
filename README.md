# Dmxs

[![CI Status](http://img.shields.io/travis/maxep/MXSegmentedPager.svg?style=flat)](https://travis-ci.org/maxep/MXSegmentedPager)
[![Version](https://img.shields.io/cocoapods/v/MXSegmentedPager.svg?style=flat)](http://cocoadocs.org/docsets/MXSegmentedPager)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/MXSegmentedPager.svg?style=flat)](http://cocoadocs.org/docsets/MXSegmentedPager)
[![Platform](https://img.shields.io/cocoapods/p/MXSegmentedPager.svg?style=flat)](http://cocoadocs.org/docsets/MXSegmentedPager)
[![Dependency Status](https://www.versioneye.com/objective-c/mxsegmentedpager/1.0/badge.svg)](https://www.versioneye.com/objective-c/mxsegmentedpager)

Dmxs test
``` C#
>
        private int GetFileNumb(string path)
        {
            int Numb = 0;
            try
            {
                string[] directories = new string[0];
                directories = Directory.GetDirectories(@"F:\Allen\Sun\Com");
                foreach (string str2 in directories)
                {
                    Numb += (new DirectoryInfo(str2)).GetFiles().Length;
                }
            }
            catch (Exception exception)
            {
                MessageBox.Show(exception.Message + " " + path);
            }
            return Numb;
        }
```
