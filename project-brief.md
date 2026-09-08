# Flood Exposure of Transit Infrastructure in Lagos Island

## Part 1: The question
Which major road segments and transit hubs in Lagos Island sit in low-lying areas highly vulnerable to flooding?

## Part 2: Why it matters
Lagos Island is a densely developed and highly active urban area where roads and public transportation infrastructure are essential for daily movement of people and goods. Because parts of the area have low-lying terrain and are influenced by intense rainfall and surrounding water bodies, flooding can disrupt transportation, damage infrastructure, and increase travel delays.

The results of this analysis can provide location-based intelligence for urban planners, civil engineers, transport authorities, and local government agencies. By identifying the road segments and transit hubs most exposed to low-lying terrain and potential flooding, decision-makers can better prioritise drainage improvements, road maintenance, flood mitigation, route-diversion planning, and infrastructure upgrades.

The project also provides a useful baseline for further engineering and geotechnical investigations into how terrain, drainage and watercourses influence transportation infrastructure.

## Part 3: The data you need
* Administrative ward boundaries for Lagos Island.
* Road networks and transit points.
* High-resolution elevation and terrain data.

## Part 4: Where each dataset comes from
| Dataset                        | Recommended Source                  | Purpose                                |
| ------------------------------ | ----------------------------------- | -------------------------------------- |
| Administrative/ward boundaries | **GRID3**                           | Define the study area                  |
| Road network                   | **OpenStreetMap via QuickOSM**      | Map and analyse road segments          |
| Transit points                 | **OpenStreetMap / HDX**             | Locate bus stops and transit hubs      |
| Elevation/DEM                  | **OpenTopography / Copernicus DEM** | Analyse elevation and terrain          |
| Watercourses/drainage          | **OpenStreetMap / HDX**             | Assess proximity to water/drainage     |
| Satellite imagery              | **Copernicus Data Space**           | Supporting land-cover analysis         |
| Population                     | **WorldPop**                        | Assess population potentially affected |
| Historical flood information   | Government/available flood datasets | Validate flood-prone locations         |


## Part 5: What you would build
The main output will be a:

Flood Exposure & Transit Infrastructure Vulnerability Map

The map will identify and classify road segments and transit hubs according to their exposure to potentially flood-prone terrain.

For example:

🟢 Low exposure
🟡 Moderate exposure
🟠 High exposure
🔴 Very high exposure

The analysis can combine elevation, slope, proximity to drainage/watercourses and other available flood-related factors to identify locations requiring further investigation.

The final map can provide a rapid spatial assessment tool for:

Identifying vulnerable road segments
Prioritising drainage improvements
Supporting road-maintenance planning
Identifying potentially vulnerable transit hubs
Planning emergency route diversions
Supporting flood-mitigation projects
Guiding further engineering and geotechnical investigations