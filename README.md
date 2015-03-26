# JZLocationConverter-for-Android
java 或者 android版本的JZLocationConverter，IOS版本请看https://github.com/JackZhouCn/JZLocationConverter

/**
* @param location 世界标准地理坐标(WGS-84)
* @return 中国国测局地理坐标（GCJ-02）<火星坐标>
* @brief 世界标准地理坐标(WGS-84) 转换成 中国国测局地理坐标（GCJ-02）<火星坐标>
*
* ####只在中国大陆的范围的坐标有效，以外直接返回世界标准坐标
*/
public static LatLng wgs84ToGcj02(LatLng location);
/**
* @param location 中国国测局地理坐标（GCJ-02）
* @return 世界标准地理坐标（WGS-84）
* @brief 中国国测局地理坐标（GCJ-02） 转换成 世界标准地理坐标（WGS-84）
*
* ####此接口有1－2米左右的误差，需要精确定位情景慎用
*/
public static LatLng gcj02ToWgs84(LatLng location);
/**
* @param location 世界标准地理坐标(WGS-84)
* @return 百度地理坐标（BD-09)
* @brief 世界标准地理坐标(WGS-84) 转换成 百度地理坐标（BD-09)
*/
public static LatLng wgs84ToBd09(LatLng location);
/**
* @param location 中国国测局地理坐标（GCJ-02）<火星坐标>
* @return 百度地理坐标（BD-09)
* @brief 中国国测局地理坐标（GCJ-02）<火星坐标> 转换成 百度地理坐标（BD-09)
*/
public static LatLng gcj02ToBd09(LatLng location) ;
/**
* @param location 百度地理坐标（BD-09)
* @return 中国国测局地理坐标（GCJ-02）<火星坐标>
* @brief 百度地理坐标（BD-09) 转换成 中国国测局地理坐标（GCJ-02）<火星坐标>
*/
public static LatLng bd09ToGcj02(LatLng location);
/**
* @param location 百度地理坐标（BD-09)
* @return 世界标准地理坐标（WGS-84）
* @brief 百度地理坐标（BD-09) 转换成 世界标准地理坐标（WGS-84）
*
* ####此接口有1－2米左右的误差，需要精确定位情景慎用
*/
public static LatLng bd09ToWgs84(LatLng location);
