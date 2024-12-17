# Air Quality Analysis Project  

## Introduction  
Air pollution is one of the world's largest health and environmental challenges. Air pollution expands in two contexts: indoor (household) air pollution and outdoor air pollution.  

Air pollution is often defined as the combination of outdoor and indoor particulate matter and ozone. It is a risk factor for many of the leading causes of death, including heart disease, stroke, lower respiratory infections, lung cancer, diabetes, and chronic obstructive pulmonary disease (COPD) *(Ritchie and Roser 2019)*.  

![Death by Factor](visualization/death%20by%20factor.png)

Unfortunately, over half of the world's population lives without the protection of adequate air quality standards.  

## Air Quality Data  
The U.S. Environmental Protection Agency (EPA) regulates six pollutants as “criteria” air pollutants using human health-based and environmentally-based criteria:  
- Ground-level ozone (OZ)  
- Particle pollution (PM2.5 and PM10)  
- Carbon monoxide (CM)  
- Lead total suspended particulate (TSP)  
- Nitrogen oxides (NO2)  
- Sulfur dioxide (SD)  

### PM2.5: The Invisible Killer  
Among all air pollutants, PM2.5 kills the most people worldwide. It consists of particles smaller than 2.5 microns — small enough that billions of PM2.5 can fit inside a single red blood cell. PM2.5 is responsible for an estimated 4.2 million premature deaths every year globally *(McGill University 2021)*.  

## Purpose  
This project creates a **visual analytics tool** to analyze, monitor, and forecast air quality for San Diego County. It tackles the challenges of air quality using advanced analytics and R-based tools.  

## Files Included  
- `data/`: Contains air quality datasets.  
- `scripts/`: R scripts and notebooks for analysis.  
- `images/`: Visualizations and images used in documentation.  
- `assignment1_notebook.Rmd`: Main RMarkdown file for Assignment 1.

  ## PM2.5 Visualizations


| PM2.5 vs PM10 | PM2.5 vs CM | PM2.5 vs NO2 |
|---------------|------------|-------------|
![PM2.5 vs PM10](visualization/pm2.5_vs_pm10.png) | ![PM2.5 vs CM](visualization/om%202.5%20vs%20cm.png) | ![PM2.5 vs NO2](visualization/pm%202.5%20vs%20NO2.png) |

| PM2.5 vs OZ | PM2.5 vs SD | Overall PM2.5 |
|-------------|------------|---------------|
| ![PM2.5 vs OZ](visualization/pm%202.5%20vs%20OZ.png) | ![PM2.5 vs SD](visualization/pm%202.5%20vs%20SD.png) | ![Overall PM2.5](visualization/pm%202.5.png) |

## PM2.5 Analysis

<table>
  <tr>
    <td><strong>Correlation Heatmap</strong></td>
    <td><strong>Safe and Unsafe PM2.5 Levels</strong></td>
  </tr>
  <tr>
    <td>
      <img src="visualization/correlation_heatmap_pollutant.png" alt="Correlation Heatmap" width="400">
    </td>
    <td>
      <img src="visualization/pm25_vs_safeunsafe.png" alt="Safe and Unsafe PM2.5" width="400">
    </td>
  </tr>
</table>






