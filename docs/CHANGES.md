# Changes
## v0.4.2
*Released on 08/02/2019*
- **[Bug Fix]** Removed redraw when map extent change event, so no duplicated measurement is drawn when the map projection spans over multiple worlds.

## v0.4.0
*Released on 11/12/2018*
- **[Enhancement]**  Expose getters for segments and points of measurements. [#45](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/issues/45)

## v0.3.0
*Released on 11/06/2018*
- **[New Feature]** Allow to pass in an array of points when starting measurement in contextMenu-disabled mode. Find the usage at the [Developer Guide](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/blob/master/docs/GUIDE.md#start-measurement-with-initial-points).

## v0.2.0
*Released on 07/02/2018*
- **[Enhancement]** Added new unit - **Nautical Miles (NM)** Details see [PR #40](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/pull/40).

## v0.1.4
*Released on 03/21/2018*
- **[Bug Fix]** Fixed a newly introduced initialization bug caused from v0.1.2. Details see [#34](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/issues/34).

## v0.1.2
*Released on 03/20/2018*
- **[Bug Fix]** Fixed an overlay bug. Details see [#12](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/issues/12).

## v0.1.1
*Released on 03/19/2018*
- **[Bug Fix]** Updated `MeasureResult` in `measure_end` listener.

## v0.1.0
*Released on 03/18/2018*
- **[New Feature]** Added `Array<Segment>` to the `MeasureResult`. Example see [#31](https://github.com/zhenyanghua/MeasureTool-GoogleMaps-V3/issues/31).
