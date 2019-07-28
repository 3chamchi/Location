# Location
두 좌표간 거리 구하기, 두 좌표 방위각 구하기, 특정 좌표에서 원하는 방향, 거리 만큼 이동한 좌표 값 구하기 (LBS, GPS, GIS, Location)

제공되는 함수
1. 두 좌표간 거리 측정, geoDistance
     * 두 좌표 거리 구하기
     * @param latitude1 Start latitude
     * @param longitude1 Start longitude
     * @param latitude2 End latitude
     * @param longitude2 End longitude
     * @return Distance(m)

2. 두 좌표의 방위각 측정, bearingP1toP2
     * 두 좌표 방위각 구하기
     * @param latitude1 Start latitude
     * @param longitude1 Start longitude
     * @param latitude2 End latitude
     * @param longitude2 End longitude
     * @return bearing

3. 특정 좌표에서 방위각 + 거리의 좌표 값 획득, geoMove
     * 특정 좌표에서 방위각, 거리를 가지고 원하는 좌표 값 획득
     * @param latitude latitude
     * @param longitude longitude
     * @param direction_degree direction
     * @param length_degree length
     * @return double[2] location = {longitude, latitude}