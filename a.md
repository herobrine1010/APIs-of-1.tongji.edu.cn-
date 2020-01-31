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
POST |  /api/commonservice/campusProfession/findProfessionByParam | 
POST |  /api/commonservice/directionMainten/addDirectionMainten | 
POST |  /api/commonservice/directionMainten/editDirectionMainten | 
POST |  /api/commonservice/directionMainten/findDirectionMaintenList | 
POST |  /api/commonservice/directionMainten/findDirectionMaintenDetail | 
POST |  /api/commonservice/directionMainten/findDirectionMaintenByProfession | 
POST |  /api/commonservice/campusProfession/findCampusMinistryRel | 
GET |  /api/commonservice/directionMainten/logicalDelDirection?grade= + e + &professionCode= + t + &code= + n | 
POST |  /api/commonservice/commonPublicMsg/findCommonPublicMsgList | 
POST |  /api/commonservice/commonMsgPublish/findHomePageCommonMsgPublish | 
GET |  /api/commonservice/commonPublicMsg/findCommonPublicMsgById?id= + e | 
POST |  /api/commonservice/commonPublicMsg/addCommonPublicMsg | 
PUT |  /api/commonservice/commonPublicMsg/updateCommonPublicMsg | 
DELETE |  /api/commonservice/commonPublicMsg/deleteCommonPublicMsg | 
PUT |  /api/commonservice/commonPublicMsg/updateTagStatus | 
POST |  /api/commonservice/commonPublicMsg/checkCommonPublicMsg | 
POST |  /api/commonservice/commonMsgPublish/findCommonMsgPublishList | 
GET |  /api/commonservice/commonMsgPublish/findCommonMsgPublishById?id= + e | 
POST |  /api/commonservice/commonMsgPublish/addCommonMsgPublish | 
PUT |  /api/commonservice/commonMsgPublish/updateCommonMsgPublish | 
DELETE |  /api/commonservice/commonMsgPublish/deleteCommonMsgPublish | 
PUT |  /api/commonservice/commonMsgPublish/updateTagStatus | 
POST |  /api/commonservice/commonMsgPublish/checkCommonMsgPublish | 
POST |  /api/userservice/userGroup/findUserGroupList | 
POST |  /api/commonservice/commonMsgPublish/findPopCommonMsgPublish | 
POST |  /api/commonservice/commonMsgPublish/addOrUpdateNoTipsMsg | 
POST |  /api/cultureservice/studentCultureRel/findStudentCultureRelList | 
PUT |  /api/cultureservice/studentCultureRel/batchUpdateFirstLanguageCourses | 
GET |  /api/cultureservice/culturePlan/getCulturePlanByStudentId?id= + e + &isPass= + t | 
GET |  u | 
POST |  /api/cultureservice/culturePlan/saveCulturePlan/ + t + / + n + / + a | 
PUT |  /api/cultureservice/culturePlan/updateCulturePlan/ + t + / + n + / + a | 
GET |  /api/cultureservice/studentCultureRel/findStudentCultureRelByStudentId?stuid= + e | 
PUT |  /api/cultureservice/studentCultureRel/updateStudentCultureRelStatus?studentId= + e + &status= + t + &teacherId= + n | 
PUT |  /api/cultureservice/studentCultureRel/autoUpdateFirstLanguageCourses | 
GET |  /api/cultureservice/studentCultureRel/result/ + e | 
POST |  /api/commonservice/dictionary/queryList | 
DELETE |  /api/cultureservice/studentCultureRel/courses | 
PUT |  /api/cultureservice/studentCultureRel/courses | 
POST |  /api/cultureservice/studentCultureRel/courses | 
POST |  /api/cultureservice/culturePlan/selectCoursesCountList | 
POST |  /api/cultureservice/culturePlan/findScorePassCountStudent | 
POST |  /api/cultureservice/culturePlan/findNoScorePassCountStudent | 
POST |  /api/cultureservice/culturePlan/findNoSelCourseCountStudent | 
POST |  /api/cultureservice/culturePlan/findSelCourseCountStudent | 
POST |  /api/cultureservice/culturePlan/transdisciplinaryCourseList | 
POST |  /api/cultureservice/culturePlan/saveTransdisciplinaryCourse | 
POST |  /api/cultureservice/courseSelectSet/addOrEditCourseSelectSet | 
GET |  /api/cultureservice/courseSelectSet/findCourseSelectSet | 
POST |  /api/cultureservice/courseSelectSet/findStudentInfoByIdList | 
GET |  /api/cultureservice/BatchOperaterPlan/batchupdate/?cultureID= + e + &oldCourseCode= + t + &newCourseCode= + n | 
GET |  /api/cultureservice/BatchOperaterPlan/batchAdd/?cultureID= + e + &labid= + t + &courseid= + n | 
GET |  /api/cultureservice/BatchOperaterPlan/batchdelete/?cultureID= + e + &oldCourseCode= + t | 
GET |  /api/cultureservice/culturePlan/studentPlanCountByStuId/?studentId= + e | 
GET |  /api/cultureservice/PowerContron/getPower | 
GET |  /api/cultureservice/PowerContron/getTurn?Type_= + e + &projId= + t | 
GET |  /api/cultureservice/PowerContron/insertPower?Type_= + e + &powerValue= + t + &projId= + n | 
GET |  /api/cultureservice/cultureAuth/findAuthPushTimePermission? + t | 
POST |  /api/cultureservice/cultureOperationLogInfo | 
POST |  /api/cultureservice/culturePlan/getSmallCourse | 
POST |  /api/cultureservice/culturePlan/setSmallCourse | 
POST |  /api/cultureservice/culturePlan/deleteTransdisciplinaryCourse | 
POST |  /api/cultureservice/firstLanguageContrast/queryAddCourseList?content= + e | 
POST |  /api/cultureservice/firstLanguageContrast/queryCourseListByCodes | 
GET |  /api/cultureservice/studentCultureRel/cancelApprove/ + e | 
POST |  /api/cultureservice/culturePlan/ischeckExitRace | 
POST |  /api/cultureservice/bclCultureScheme/findSchemeByPage | 
POST |  /api/cultureservice/bclCultureScheme/findCultureForBlind | 
POST |  /api/cultureservice/bclStudentCultureRel/countNeedBindSchemeStudent | 
POST |  /api/cultureservice//bclStudentCultureRel/bindSchemeStudent | 
GET |  /api/cultureservice/bclCultureScheme/blindScheme + i(e) | 
GET |  /api/cultureservice/bclCultureScheme/cancelBlind + i(e) | 
GET |  /api/cultureservice/bclCultureScheme/findSecondScheme + i(e) | 
GET |  /api/cultureservice/bclCultureScheme/saveSecondScheme + i(e) | 
POST |  /api/studentservice/studentInfo/findStuInfoList | 
POST |  /api/studentservice/studentInfo/findViewColumnByTable | 
GET |  /api/studentservice/studentDic/getByTableName? + e | 
GET |  /api/studentservice/configOptions/getConOptList | 
POST |  /api/studentservice/configOptions/saveConfigInfo | 
GET |  /api/studentservice/configOptions/getConfigInfo? + e | 
POST |  /api/studentservice/studentInfo/saveEditColumnVal | 
GET |  /api/studentservice/studentInfo/findEidtAcaEduColumn/ | 
POST |  /api/studentservice/studentInfo/checkEditAcaEduColumnVal | 
POST |  /api/studentservice/teacherInfo/findTeacherInfoList | 
POST |  /api/studentservice/abnormal/template | 
POST |  /api/studentservice/abnormal/apply | 
PUT |  /api/studentservice/abnormal/template | 
POST |  /api/studentservice/studentDetailInfo/stuDetailByClass | 
POST |  /api/studentservice/studentDetailInfo/stuDetailSubmit | 
POST |  /api/studentservice/configOptions/getApproRoles | 
GET |  /api/studentservice/configOptions/getApproUser?roleId= + e + &type= + t + &configId= + n | 
POST |  /api/studentservice/configOptions/getApproFields | 
POST |  /api/studentservice/configOptions/addFieldRoleConfig | 
POST |  /api/studentservice/stuAppoint/getAppointList | 
POST |  /api/studentservice/stuAppoint/getNoAppointStuList | 
POST |  /api/studentservice/stuAppoint/selectedStu | 
POST |  /api/studentservice/stuAppoint/getAppointTeaList | 
POST |  /api/studentservice/stuAppoint/appointTea | 
POST |  /api/studentservice/stuAppoint/deleteAppointTea | 
POST |  /api/studentservice/stuActivation/addConfig | 
POST |  /api/studentservice/stuActivation/configList | 
POST |  /api/studentservice/stuActivation/updateConfig | 
GET |  /api/studentservice/stuActivation/deleteConfig?configId= + e | 
POST |  /api/studentservice/stuActivation/fieldConfig | 
POST |  /api/studentservice/stuActivation/singleConfig | 
POST |  /api/studentservice/stuActivation/activationList | 
POST |  /api/studentservice/studentDetailInfo/colSchSubmit | 
POST |  /api/studentservice/stuActivation/activation | 
POST |  /api/studentservice/fieldLog/getLogList | 
GET |  /api/studentservice/studentDetailInfo/getVisibleTabList?studentId= + e | 
GET |  /api/studentservice/configOptions/getAllApproFields?configId= + e | 
GET |  /api/studentservice/studentDic/findAllStuDicts | 
POST |  /api/studentservice/studentInfo/findStuInfoListForSelect | 
GET |  /api/studentservice/configOptions/checkSelectedFile | 
POST |  /api/cultureservice/coursesCategory | 
POST |  /api/cultureservice/coursesCategory/list | 
DELETE |  /api/cultureservice/coursesCategory | 
PUT |  /api/cultureservice/coursesCategory | 
GET |  /api/cultureservice/coursesCategory/ + e | 
POST |  /api/cultureservice/coursesCategoryLabel/ | 
POST |  /api/cultureservice/coursesCategoryLabel/list | 
DELETE |  /api/cultureservice/coursesCategoryLabel | 
GET |  /api/cultureservice/coursesCategoryLabel/ + e | 
PUT |  /api/cultureservice/coursesCategoryLabel | 
GET |  /api/cultureservice/coursesLabel/sonList | 
POST |  /api/cultureservice/coursesCategoryRel | 
POST |  /api/cultureservice/coursesCategoryRel/list | 
DELETE |  /api/cultureservice/coursesCategoryRel | 
GET |  /api/cultureservice/coursesCategoryRel/ + e | 
PUT |  /api/cultureservice/coursesCategoryRel | 
PUT |  /api/cultureservice/coursesCategoryRel/Label | 
POST |  /api/welcomeservice/taskTemplate/findTaskTemplateLimit | 
POST |  /api/welcomeservice/taskTemplate/listWithoutDetails | 
POST |  /api/welcomeservice/taskTemplate/selectTaskTemplateById | 
PUT |  /api/welcomeservice/taskInfo | 
POST |  /api/welcomeservice/taskTemplate | 
PUT |  /api/welcomeservice/taskTemplate | 
DELETE |  /api/welcomeservice/taskTemplate | 
POST |  /api/welcomeservice/taskTemplate/releaseTaskTemplate | 
POST |  /api/welcomeservice/taskTemplate/undoTaskTemplate | 
POST |  /api/welcomeservice/taskTemplate/copyTaskTemplate | 
POST |  /api/welcomeservice/taskTemplate/selectTaskTemplateByStudents | 
POST |  /api/welcomeservice/taskInfo | 
GET |  /api/welcomeservice/taskInfo/exportTaskInfoByStudent + t | 
POST |  /api/welcomeservice/taskStudent/ | 
GET |  /api/welcomeservice/taskTemplate/ | 
GET |  /api/welcomeservice/taskTemplate/dictionary/ + e | 
IS.FIELDSAPIMETHOD |  this.fieldsApi | 
POST |  this.preUrl + filterFieldCondi | 
IS.SEARCHAPIMETHOD |  this.searchApi | 
POST |  this.preUrl + addAdvancedQuery | 
GET |  e.preUrl + deleteAdvancedScheme?schemeId= + e.selectedSchemeId | 
.FIELDSAPIMETHOD |  t.fieldsApi | 
POST |  e.preUrl + addAdvancedImpExp | 
POST |  this.preUrl + addAdvancedImpExp | 
GET |  e.preUrl + deleteAdvanImpExpScheme?schemeId= + e.selectedSchemeId | 
POST |  /api/studentservice/studentInfo/findAllStuInfoList | 
POST |  /api/arrangementservice/teachingTask/page2 | 
POST |  /api/arrangementservice/teachingTask/findResearchRoom | 
GET |  i | 
POST |  /api/arrangementservice/teachingTask/ + e + /profession/add | 
POST |  /api/arrangementservice/teachingTask/ + e + /class/add | 
POST |  /api/arrangementservice/teachingTask/ + e + /class/update | 
POST |  /api/arrangementservice/teachingTask/ + e + /class/delete | 
POST |  /api/arrangementservice/teachingTask/ + e + /profession/delete | 
POST |  /api/arrangementservice/teachingTask/ + e + /profession/update | 
POST |  /api/arrangementservice/teachingTask/ + e + /class/merge | 
POST |  /api/arrangementservice/teachingTask/ + e + /class/split | 
GET |  /api/arrangementservice/publicelective/ + e | 
POST |  /api/arrangementservice/professioncampusnum/findCampus | 
POST |  /api/arrangementservice/professioncampusnum/findSelectList | 
GET |  /api/cultureservice/coursesLabel/coursesLabelList | 
POST |  /api/cultureservice/coursesLabel/getCoursesLabelList | 
POST |  /api/arrangementservice/teachingTask/export | 
GET |  /api/arrangementservice/teachingTask/ + e + /class/newcode | 
POST |  /api/arrangementservice/teachingTask/updateBatch | 
GET |  /api/arrangementservice/teachingTask/result/ + e | 
POST |  /api/arrangementservice/teachingTask/deleteTask | 
POST |  /api/baseresservice/teacher/findTeacherList | 
POST |  /api/baseresservice/teacher/progressTeacherList | 
POST |  /api/baseresservice/teacher/checkTeacherAuth | 
POST |  /api/baseresservice/teacherTitle/findTeacherTitleList | 
PUT |  /api/baseresservice/teacherTitle/batchNeedTeacherTitle | 
PUT |  /api/baseresservice/teacherTitle/batchNoNeedTeacherTitle | 
PUT |  /api/baseresservice/teacher/batchUpdApprovalStatus | 
POST |  api/baseresservice/teacher/findList?condition= + e | 
POST |  api/baseresservice/teacher | 
DELETE |  api/baseresservice/teacher | 
GET |  api/baseresservice/teacher/findTeacherById?id= + e | 
GET |  api/baseresservice/teacher/findTeacherBycode?code= + e | 
GET |  api/baseresservice/teacher/ + e | 
PUT |  api/baseresservice/teacher | 
PUT |  api/baseresservice/teacher/status | 
POST |  api/baseresservice/teacher/title | 
POST |  api/baseresservice/teacher/time/up | 
POST |  api/baseresservice/teacher/time | 
POST |  api/baseresservice/teacher/template/upload?path= + e | 
GET |  api/baseresservice/teacher/template/path | 
PUT |  api/baseresservice/teacher/teachQual | 
POST |  api/baseresservice/teacher/list?condition= + e | 
POST |  api/baseresservice/teacher/apply/list | 
POST |  api/baseresservice/teacher/checkTeacherAuth | 
POST |  api/baseresservice/teacher/approval/list | 
POST |  api/baseresservice/teacher/exportTeacherList | 
GET |  api/baseresservice/teacher/result/ + e | 
GET |  /api/commonservice/obsfile/downloadimage?objectkey= + e | 
POST |  this.url | 
POST |  /api/cultureservice/BclCulturePlanOpen/findBclCultureOpen | 
POST |  /api/cultureservice/BclCulturePlanOpen/insertCultureOpen | 
POST |  /api/cultureservice/BclCulturePlanOpen/updateCultureOpen | 
GET |  /api/cultureservice/BclCulturePlanOpen/findDepartMent + Bt(e) | 
GET |  /api/cultureservice/BclCulturePlanOpen/deleteCultureOpen + Bt(e) | 
GET |  /api/workflow/approval/selectApproFlow + Xt(e) | 
POST |  /api/workflow/approval/selectApproFlowList | 
POST |  /api/workflow/approval/reject/batch | 
POST |  /api/workflow/approval/through/batch | 
POST |  /api/workflow/approval/getMyApprovalTask | 
GET |  /api/studentservice/studentInfo/findUserInfoByIdType + Xt(e) | 
POST |  /api/workflow/approval/through | 
POST |  /api/workflow/approval/reject | 
POST |  /api/cultureservice/bclCulturePlan/findStudentPlanList | 
POST |  /api/cultureservice/bclCulturePlan/findCultureSchemeList | 
POST |  /api/cultureservice/bclCulturePlan/saveOrCommitPlan/ + t.type + / + t.studentID + / + t.schemeID + / + t.msg | 
POST |  /api/cultureservice/bclCulturePlan/chekCommit/ + t.type + / + t.studentID + / + t.schemeID | 
GET |  /api/cultureservice/bclCulturePlan/blindScheme + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/cancelBlind + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/findSecondScheme + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/saveSecondScheme + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/canCelCommit + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/findStudentInfo + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/countCredit + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/findPlanCourseTab + nn(e) | 
GET |  /api/cultureservice/bclCulturePlan/findMadePlanCourseTab + nn(e) | 
POST |  /api/cultureservice/BclCulturePlanOpen/isOpen | 
POST |  /api/cultureservice/bclCulturePlan/selectCoursesCountList | 
POST |  /api/cultureservice/bclCulturePlan/ + t | 
POST |  /api/cultureservice/bclCulturePlan/renovate | 
GET |  /api/cultureservice/bclHonorModule/honorModuleList | 
GET |  /api/cultureservice/bclHonorModule/honorDirectionList?moduleId= + e | 
GET |  /api/electionservice/honorPlanStds/download | 
POST |  /api/electionservice/honorPlanStds/export | 
PUT |  /api/electionservice/honorPlanStds | 
POST |  /api/electionservice/honorPlanStds/delete | 
GET |  /api/electionservice/reportManagement/getTeacherTimetable?calendarId= + e + &week= + t | 
GET |  /api/electionservice/reportManagement/getStudentTimetab?calendarId= + e + &week= + t | 
POST |  /api/sessionservice/session/login | 
POST |  /api/sessionservice/session/localLogin | 
POST |  /api/sessionservice/session/logout | 
PUT |  /api/sessionservice/session/setLanguage | 
POST |  /api/sessionservice/session/mock | 
PUT |  /api/sessionservice/session/mockOff | 
GET |  /api/sessionservice/session/getSessionUser | 
GET |  /api/sessionservice/session/ping | 
GET |  /api/sessionservice/session/getSessionByCurrentManageDptId?currentManageDptId= + e | 
GET |  /api/sessionservice/session/getSessionByCurrentRole?currentRole= + e.currentRole + &flag= + e.flag | 
POST |  /api/userservice/authorityMenu/findAuthorityMenuList | 
POST |  /api/userservice/authorityMenu/findMenuListPage | 
GET |  /api/userservice/authorityMenu/findMeunById/ + e | 
POST |  /api/userservice/authorityMenu/addAuthorityMenu | 
DELETE |  /api/userservice/authorityMenu/deleteAuthorityMenu/ + e | 
POST |  /api/userservice/authorityMenu/updateAuthorityMenu | 
POST |  /api/userservice/authorityMenu/orderMenus | 
POST |  /api/userservice/userGroup/findGroupList | 
GET |  /api/userservice/userGroup/getGroup | 
POST |  /api/userservice/userGroup/findUnbindGroupList | 
POST |  /api/userservice/role/findRoleList | 
POST |  /api/userservice/role/findUnbindRoleList | 
POST |  /api/userservice/userGroup/addGroup | 
POST |  /api/userservice/localUser/findLocalUserList | 
POST |  /api/userservice/localUser/addLocalUser | 
POST |  /api/userservice/localUser/findLocalUserListNotInGroupId | 
PUT |  /api/userservice/localUser/updateLocalUser | 
POST |  /api/userservice/userGroup/batchAddUserGroupRel | 
POST |  /api/userservice/userGroup/findGroupNotInListByUserId | 
PUT |  /api/userservice/userGroup/updateGroup | 
POST |  /api/userservice/userGroup/findGroupListByUserId | 
PUT |  /api/userservice/role/updateRole | 
POST |  /api/userservice/role/addRole | 
GET |  /api/userservice/role/getAuthOrDeptRelListByRoleId? + e | 
POST |  /api/userservice/userGroup/batchAddRoleGroupRel | 
DELETE |  /api/userservice/role/batchDelGroupRelByRoleId | 
POST |  /api/userservice/role/batchAddGroupRelByRoleId | 
POST |  /api/userservice/role/batchAddAuthOrDeptToRoleRel | 
POST |  /api/userservice/userGroup/getUserInfoListByGroupId | 
POST |  /api/userservice/userGroup/getUserInfoListNotInGroupId | 
DELETE |  /api/userservice/userGroup/batchDelUserGroupRel | 
DELETE |  /api/userservice/role/deleteRole? + e | 
DELETE |  /api/userservice/role/batchDelAuthOrDeptToRoleRel | 
GET |  /api/userservice/role/getGroupListByRoleId? + e | 
GET |  /api/userservice/role/getGroupListNotInRoleId? + e | 
DELETE |  /api/userservice/localUser/deleteLocalUser | 
GET |  /api/userservice/localUser/unlockLocalUser?userId= + e | 
DELETE |  /api/userservice/userGroup/deleteGroup? + e | 
GET |  /api/userservice/dept/findDept?virtualDept=0&type=0 | 
GET |  /api/userservice/dept/findDept?virtualDept= + t | 
POST |  /api/userservice/dept/findAllDepartmentList | 
DELETE |  /api/userservice/dept/deleteDeptList | 
POST |  /api/userservice/dept/addDept | 
PUT |  /api/userservice/dept/updateDept | 
GET |  /api/userservice/authorityMenu/findAllInfoAuthByUserId? + e | 
POST |  /api/studentservice/teacherInfo/findTeacherInfoListNotInGroupId | 
GET |  /api/studentservice/studentInfo/findUserInfoByIdType? + t | 
GET |  /api/userservice/localUser/findLocalUserById? + e | 
GET |  /api/studentservice/studentInfo/findUserInfoByType? + t | 
DELETE |  /api/userservice/userGroup/batchDelGroupRelByUser | 
GET |  /api/studentservice/teacherInfo/findTeacherInfoBycode | 
POST |  /api/studentservice/teacherInfo/findTopTenUserList | 
POST |  /api/studentservice/teacherInfo/findTopTenTeacherList | 
POST |  /api/userservice/userGroup/getRoleRelListByGroupId | 
DELETE |  /api/userservice/userGroup/batchDelRoleGroupRel | 
POST |  /api/studentservice/userInfo/batchUserGroupRelByCondition | 
DELETE |  /api/studentservice/userInfo/batchDelUserGroupRelByCondition | 
GET |  /api/userservice/authorityMenu/findGroupRoleByAuthAndUserId | 
POST |  /api/userservice/authPushTime/findAuthPushTimeListPage | 
DELETE |  /api/userservice/authPushTime/deleteAuthPushTime | 
POST |  /api/userservice/authPushTime/deleteAuthPushTimeByIds | 
POST |  /api/userservice/authPushTime/addAuthPushTime | 
PUT |  /api/userservice/authPushTime/updateAuthPushTime | 
GET |  /api/userservice/authPushTime/findAuthPushTimeById? + e | 
POST |  /api/userservice/userGroupData/createOrDelOrUpdateGroupData | 
GET |  /api/userservice/userGroupData/findUserGroupDataByUserGroupId | 
GET |  /api/userservice/authPushTime/findAuthPushTimePermissionPage? + t | 
PUT |  /api/userservice/localUser/updateLoginMark | 
GET |  /api/userservice/localUser/getLoginMark | 
GET |  /api/userservice/dept/findDept?virtualDept= + e + &type= + t + &manageDept= + n | 
GET |  /api/userservice/dept/findManageDepartment | 
PUT |  /api/studentservice/teacherInfo/updateTeacher | 
GET |  /api/studentservice/studentEduBackg/findEduBackgroudList | 
GET |  /api/studentservice/studentEduBackg/findEduBackgroud | 
POST |  /api/studentservice/studentEduBackg/addEduBackgroud | 
POST |  /api/studentservice/studentEduBackg/updateEduBackgroud | 
DELETE |  /api/studentservice/studentEduBackg/deleteEduBackgroud | 
