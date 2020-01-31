method|url|comment
-|-|-
DELETE |  /api/electionservice/electionRound | 
GET |  /api/electionservice/electionRound/ + e | 
POST |  /api/electionservice/electionRound | 
PUT |  /api/electionservice/electionRound | 
POST |  /api/electionservice/electionRound/page | 
GET |  /api/electionservice/rebuildCourse/selectLabelName?calendarId= + e | 
POST |  /api/electionservice/rebuildCourse/selectTurn | 
POST |  /api/electionservice/rebuildCourse/deleteRecycleCourse | 
POST |  /api/electionservice/electionRound/pageTj | 
POST |  /api/commonservice/dictionary/query | 
POST |  /api/commonservice/dictionary/getDictionaryForList | 
POST |  /api/commonservice/dictionary/insertDict | 
PUT |  /api/commonservice/dictionary/updateDict | 
DELETE |  /api/commonservice/dictionary/dict | 
PUT |  /api/commonservice/dictionary/updateDictType | 
GET |  /api/commonservice/dictionary/getDictById/ + e | 
GET |  /api/commonservice/dictionary/getDictionarys/type | 
GET |  /api/commonservice/dictionary/refreshCache | 
POST |  /api/commonservice/dictionary/getDictList/page/ + e + / + t | 
GET |  /api/commonservice/dictionary/findDictTypeByRelateType?relateType= + e | 
GET |  /api/commonservice/dictionary/findTrainingLevelByProjId + (e ? ?projId= + e : ) | 
POST |  /api/commonservice/dictionary/queryDictByCondition | 
POST |  /api/userservice/dept/findDeptForClassroom | 
GET |  /api/welcomeservice/examinationList/selectExaminationNameByTemplateId | 
GET |  /api/welcomeservice/examinationScore/selectScoreNameByTemplateId | 
POST |  /api/welcomeservice/examinationList | 
POST |  /api/welcomeservice/examinationScore | 
POST |  /api/welcomeservice/examinationList/selectExaminationListPage | 
POST |  /api/welcomeservice/examinationScore/selectExaminationScoreListPage | 
DELETE |  /api/welcomeservice/examinationList | 
DELETE |  /api/welcomeservice/examinationScore | 
GET |  /api/commonservice/commonMessage/findTopFiveCommonMessage | 
POST |  /api/commonservice/commonMessage/findCommonMessageList | 
GET |  /api/commonservice/commonMessage/countCommonMessage | 
DELETE |  /api/commonservice/commonMessage/deleteCommonMessage | 
PUT |  /api/commonservice/commonMessage/updateTagStatus | 
PUT |  /api/commonservice/commonMessage/updateAllTagStatus | 
DELETE |  /api/baseresservice/schoolCalendar | 
PUT |  /api/baseresservice/schoolCalendar | 
POST |  /api/baseresservice/schoolCalendar | 
GET |  /api/baseresservice/schoolCalendar/ + e | 
GET |  /api/baseresservice/schoolCalendar/export/ + e | 
GET |  /api/baseresservice/schoolCalendar/currentTermCalendar | 
GET |  /api/baseresservice/schoolCalendar/page | 
GET |  /api/baseresservice/schoolCalendar/list | 
GET |  /api/baseresservice/schoolCalendar/nextTermCalendar | 
GET |  /api/baseresservice/schoolCalendar/lastTermCalendar?calendarId= + e | 
GET |  /api/baseresservice/schoolCalendar/result/time?time= + e | 
GET |  /api/baseresservice/schoolCalendar/time?id= + e + &weekNum= + t + &weekDay= + n | 
POST |  /api/baseresservice/classroomController/getClassroomInfoList | 
POST |  /api/baseresservice/classroom/addClassroom | 
GET |  /api/baseresservice/towerManagement/findTowerManagementList | 
GET |  /api/baseresservice/classroom/findClassroomByCode | 
POST |  /api/baseresservice/classroomController/getClassroomListInfo?pageNum_= + e + &pageSize_= + t | 
GET |  /api/baseresservice/classroomController/selectClassRoomStage | 
GET |  /api/baseresservice/classroomTowerInfo/getTowerByCampus | 
POST |  /api/baseresservice/classroomController | 
PUT |  /api/baseresservice/classroomController | 
DELETE |  /api/baseresservice/classroomController | 
POST |  /api/baseresservice/classroomController/batchEditClassroomInfo | 
POST |  /api/baseresservice/classroomTowerInfo/list | 
POST |  /api/baseresservice/classroomTowerInfo | 
PUT |  /api/baseresservice/classroomTowerInfo | 
DELETE |  /api/baseresservice/classroomTowerInfo | 
POST |  /api/baseresservice/classroomBroTeacherRel/getListInfo | 
POST |  /api/baseresservice/classroomBroTeacherRel | 
DELETE |  /api/baseresservice/classroomBroTeacherRel | 
POST |  /api/baseresservice/classroomController/getFreeClassroomInoList | 
POST |  /api/baseresservice/classroomController/getCanBorrowClassroomIList | 
POST |  /api/baseresservice/classroomApply/getApplyListInfo | 
POST |  /api/baseresservice/classroomApply | 
PUT |  /api/baseresservice/classroomApply | 
POST |  /api/baseresservice/classroomApply/getApplyListInfoByReview | 
POST |  /api/baseresservice/classroomApply/batchApproved | 
GET |  /api/baseresservice/classroomApply/getApplyInfoByWorkflowNo/ + e | 
POST |  /api/baseresservice/classroomController/getClassroomBasalInfoList | 
POST |  /api/baseresservice/classroomTowerInfo/conditionQueryByDict | 
POST |  /api/baseresservice/classroomOccupation/getUsageCountClassroomInfoList | 
POST |  /api/baseresservice/classroomOccupation/classroomTeachingWeekDetail | 
POST |  /api/baseresservice/classroomOccupation/classroomUsageReportCountQuery | 
POST |  /api/baseresservice/classroomOccupation/getClassroomUsageRateByWeek | 
POST |  /api/baseresservice/classroomOccupation/getClassroomUsageRateByTime | 
GET |  /api/cultureservice/coursesLabel/page + t | 
GET |  /api/cultureservice/coursesLabel/coursesLabelList + t | 
POST |  /api/cultureservice/coursesLabel | 
DELETE |  /api/cultureservice/coursesLabel | 
GET |  api/cultureservice/coursesLabel/ + e | 
PUT |  /api/cultureservice/coursesLabel | 
GET |  /api/cultureservice/cultureTemplate/page + t | 
POST |  /api/cultureservice/cultureTemplate | 
GET |  /api/cultureservice/cultureTemplate/ + e | 
DELETE |  /api/cultureservice/cultureTemplate | 
POST |  /api/cultureservice/cultureRule/batchUpdCultureRule | 
GET |  /api/cultureservice/cultureTemplate/coursesLabelList/ + e + ?type= + t | 
POST |  /api/cultureservice/courses/page | 
POST |  /api/cultureservice/courses/TrainingProgram | 
POST |  /api/cultureservice/courses/queryNormalCourseList | 
POST |  /api/cultureservice/courses/queryAddCourseList | 
GET |  api/cultureservice/courses/cultureScheme/ + e + ?pageNum_= + t + &pageSize_= + n | 
POST |  api/cultureservice/courses/autoCode | 
POST |  api/cultureservice/courses/template/upload?path= + e + &&managerDeptId= + t | 
GET |  api/cultureservice/courses/template/path?managerDeptId= + e | 
GET |  /api/cultureservice/courseLabelRelation/list/ + e + ?type= + t | 
POST |  /api/cultureservice/courseLabelRelation | 
PUT |  /api/cultureservice/courseLabelRelation | 
DELETE |  /api/cultureservice/courseLabelRelation/ + e | 
PUT |  /api/cultureservice/cultureTemplate/release | 
GET |  /api/cultureservice/coursesLabel/coursesLabelTreeList | 
POST |  /api/cultureservice/cultureRule/batchSaveCultureRule | 
POST |  /api/cultureservice/cultureRule/findCheckedCultureLabelList | 
POST |  /api/cultureservice/cultureTemplate/copyCultureTemplate | 
POST |  /api/cultureservice/courseLabelRelation/copyBackCourseLabelRelation | 
POST |  /api/cultureservice/courseLabelRelation/copyBackAllCourseLabelRelation | 
GET |  /api/cultureservice/courseLabelRelation/getCourseLabelRelGroupMember?parentId= + e + &type= + t | 
POST |  /api/cultureservice/cultureScheme/findCultureSchemeListByYear | 
GET |  /api/cultureservice/courses/findCourseByCode?code= + e | 
POST |  /api/cultureservice/courses/getCoursesBycode?pageNum_= + e + &pageSize_= + t | 
GET |  /api/cultureservice/cultureScheme/updateSchemeStatus?id= + e | 
POST |  api/baseresservice/payment/pay | 
POST |  api/baseresservice/payment/callbackUrl | 
POST |  /api/electionservice/graduateExamStudentManage/listRoom | 
POST |  /api/electionservice/graduateExamStudentManage/listStudent | 
POST |  /api/electionservice/graduateExamStudentManage/listCourse | 
POST |  /api/electionservice/graduateExamStudentManage/export | 
POST |  /api/electionservice/graduateExamStudentManage/deleteExamStudent | 
POST |  /api/electionservice/graduateExamStudentManage/changeExamStudentRoom?examRoomId= + t + &examInfoId= + n | 
POST |  /api/electionservice/graduateExamStudentManage/addExamStudent | 
GET |  /api/electionservice/graduateExamStudentManage/getExamRoomByExamInfoId?examInfoIds= + e | 
GET |  /api/electionservice/reportManagement/result/ + e | 
POST |  /api/electionservice/graduateExamStudentManage/setExamStudentSituatiion?examSituation= + t | 
POST |  /api/electionservice/graduateExamStudentManage/getRoomsByCourseCode | 
GET | /api/commonservice/commonparam+ /value/ + e | 
GET | /api/commonservice/commonparam+ /groups | 
POST | /api/commonservice/commonparam+ /group | 
PUT | /api/commonservice/commonparam+ /group/ + e | 
DELETE | /api/commonservice/commonparam+ /group/ + e | 
GET | /api/commonservice/commonparam+ /param/ + e | 
POST | /api/commonservice/commonparam+ /param/ + e | 
PUT | /api/commonservice/commonparam+ /param/ + e | 
DELETE | /api/commonservice/commonparam+ /param/ + e | 
GET | /api/commonservice/commonparam+ /param/page/ + e + ?pageNum= + t + &pageSize= + n | 
POST |  /api/commonservice/campusProfession/findCampusProfessionList | 
POST |  /api/commonservice/campusProfession/addCampusProfession | 
POST |  /api/commonservice/campusProfession/editCampusProfession | 
GET |  /api/commonservice/campusProfession/findCampusProfessionById?id= + e | 
DELETE |  /api/commonservice/campusProfession/deleteCampusProfession?id= + e | 
POST |  /api/commonservice/campusProfession/copyCampusProfession | 
POST |  /api/commonservice/campusProfession/findProfessionByP
