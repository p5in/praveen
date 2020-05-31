(window["webpackJsonp"] = window["webpackJsonp"] || []).push([["pages-feed-feed-module"],{

/***/ "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/feed/feed.page.html":
/*!*********************************************************************************!*\
  !*** ./node_modules/raw-loader/dist/cjs.js!./src/app/pages/feed/feed.page.html ***!
  \*********************************************************************************/
/*! exports provided: default */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony default export */ __webpack_exports__["default"] = ("<ion-header>\n  <ion-toolbar color=\"mango\">\n    <ion-buttons slot=\"end\">\n      <ion-button (click)=\"addStudent()\">\n        Add New\n      </ion-button>\n    </ion-buttons>\n    <ion-title>Student Feed</ion-title>\n  </ion-toolbar>\n</ion-header>\n\n<ion-content class=\"ion-padding-top\">\n  <ion-list *ngFor=\"let student of students\">\n    <ion-item-sliding>\n      <ion-item>\n        <ion-avatar slot=\"start\">\n          <div class=\"avatar\">\n            {{student.name.substring(0,1).toUpperCase()}}\n          </div>\n        </ion-avatar>\n        <ion-label>\n          <h3 class=\"title\">{{student.name}}</h3>\n          <p class=\"subtext\">\n            {{'From ' + student.address + ', Tel ' + student.phone}}\n          </p>\n        </ion-label>\n      </ion-item>\n      <ion-item-options side=\"end\">\n        <ion-item-option color=\"danger\" (click)=\"removeStudent(student.id)\">\n          <ion-icon name=\"trash\"></ion-icon>delete\n        </ion-item-option>\n        <ion-item-option color=\"primary\" (click)=\"updatedStudent(student)\">\n          <ion-icon name=\"create-outline\"></ion-icon>edit</ion-item-option\n        >\n      </ion-item-options>\n    </ion-item-sliding>\n  </ion-list>\n</ion-content>\n");

/***/ }),

/***/ "./src/app/pages/feed/feed-routing.module.ts":
/*!***************************************************!*\
  !*** ./src/app/pages/feed/feed-routing.module.ts ***!
  \***************************************************/
/*! exports provided: FeedPageRoutingModule */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "FeedPageRoutingModule", function() { return FeedPageRoutingModule; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
/* harmony import */ var _angular_router__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @angular/router */ "./node_modules/@angular/router/__ivy_ngcc__/fesm2015/router.js");
/* harmony import */ var _feed_page__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! ./feed.page */ "./src/app/pages/feed/feed.page.ts");




const routes = [
    {
        path: '',
        component: _feed_page__WEBPACK_IMPORTED_MODULE_3__["FeedPage"]
    }
];
let FeedPageRoutingModule = class FeedPageRoutingModule {
};
FeedPageRoutingModule = Object(tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"])([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
        imports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"].forChild(routes)],
        exports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"]],
    })
], FeedPageRoutingModule);



/***/ }),

/***/ "./src/app/pages/feed/feed.module.ts":
/*!*******************************************!*\
  !*** ./src/app/pages/feed/feed.module.ts ***!
  \*******************************************/
/*! exports provided: FeedPageModule */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "FeedPageModule", function() { return FeedPageModule; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
/* harmony import */ var _angular_common__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @angular/common */ "./node_modules/@angular/common/__ivy_ngcc__/fesm2015/common.js");
/* harmony import */ var _angular_forms__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! @angular/forms */ "./node_modules/@angular/forms/__ivy_ngcc__/fesm2015/forms.js");
/* harmony import */ var _ionic_angular__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(/*! @ionic/angular */ "./node_modules/@ionic/angular/__ivy_ngcc__/fesm2015/ionic-angular.js");
/* harmony import */ var _feed_routing_module__WEBPACK_IMPORTED_MODULE_5__ = __webpack_require__(/*! ./feed-routing.module */ "./src/app/pages/feed/feed-routing.module.ts");
/* harmony import */ var _feed_page__WEBPACK_IMPORTED_MODULE_6__ = __webpack_require__(/*! ./feed.page */ "./src/app/pages/feed/feed.page.ts");
/* harmony import */ var _components_components_module__WEBPACK_IMPORTED_MODULE_7__ = __webpack_require__(/*! ../../components/components.module */ "./src/app/components/components.module.ts");








let FeedPageModule = class FeedPageModule {
};
FeedPageModule = Object(tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"])([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
        imports: [
            _angular_common__WEBPACK_IMPORTED_MODULE_2__["CommonModule"],
            _angular_forms__WEBPACK_IMPORTED_MODULE_3__["FormsModule"],
            _ionic_angular__WEBPACK_IMPORTED_MODULE_4__["IonicModule"],
            _components_components_module__WEBPACK_IMPORTED_MODULE_7__["ComponentsModule"],
            _feed_routing_module__WEBPACK_IMPORTED_MODULE_5__["FeedPageRoutingModule"],
        ],
        declarations: [_feed_page__WEBPACK_IMPORTED_MODULE_6__["FeedPage"]],
    })
], FeedPageModule);



/***/ }),

/***/ "./src/app/pages/feed/feed.page.scss":
/*!*******************************************!*\
  !*** ./src/app/pages/feed/feed.page.scss ***!
  \*******************************************/
/*! exports provided: default */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony default export */ __webpack_exports__["default"] = (".avatar {\n  background-color: blueviolet;\n  width: 100%;\n  height: 100%;\n  border-radius: 50px;\n  display: flex;\n  justify-content: center;\n  align-items: center;\n  color: aliceblue;\n}\n\n.subtext {\n  font-size: 80%;\n  margin-top: 0;\n  color: #8b979f;\n}\n\n.title {\n  font-weight: 600;\n  font-size: 16px;\n}\n/*# sourceMappingURL=data:application/json;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbIi9ob21lL3ByYXZlZW4vcHJvamVjdHMvaW9uaWMvcHJhdi9zcmMvYXBwL3BhZ2VzL2ZlZWQvZmVlZC5wYWdlLnNjc3MiLCJzcmMvYXBwL3BhZ2VzL2ZlZWQvZmVlZC5wYWdlLnNjc3MiXSwibmFtZXMiOltdLCJtYXBwaW5ncyI6IkFBQUE7RUFDRSw0QkFBQTtFQUNBLFdBQUE7RUFDQSxZQUFBO0VBQ0EsbUJBQUE7RUFDQSxhQUFBO0VBQ0EsdUJBQUE7RUFDQSxtQkFBQTtFQUNBLGdCQUFBO0FDQ0Y7O0FERUE7RUFDRSxjQUFBO0VBQ0EsYUFBQTtFQUNBLGNBQUE7QUNDRjs7QURFQTtFQUNFLGdCQUFBO0VBQ0EsZUFBQTtBQ0NGIiwiZmlsZSI6InNyYy9hcHAvcGFnZXMvZmVlZC9mZWVkLnBhZ2Uuc2NzcyIsInNvdXJjZXNDb250ZW50IjpbIi5hdmF0YXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiBibHVldmlvbGV0O1xuICB3aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiAxMDAlO1xuICBib3JkZXItcmFkaXVzOiA1MHB4O1xuICBkaXNwbGF5OiBmbGV4O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgY29sb3I6IGFsaWNlYmx1ZTtcbn1cblxuLnN1YnRleHQge1xuICBmb250LXNpemU6IDgwJTtcbiAgbWFyZ2luLXRvcDogMDtcbiAgY29sb3I6ICM4Yjk3OWY7XG59XG5cbi50aXRsZSB7XG4gIGZvbnQtd2VpZ2h0OiA2MDA7XG4gIGZvbnQtc2l6ZTogMTZweDtcbn1cbiIsIi5hdmF0YXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiBibHVldmlvbGV0O1xuICB3aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiAxMDAlO1xuICBib3JkZXItcmFkaXVzOiA1MHB4O1xuICBkaXNwbGF5OiBmbGV4O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgY29sb3I6IGFsaWNlYmx1ZTtcbn1cblxuLnN1YnRleHQge1xuICBmb250LXNpemU6IDgwJTtcbiAgbWFyZ2luLXRvcDogMDtcbiAgY29sb3I6ICM4Yjk3OWY7XG59XG5cbi50aXRsZSB7XG4gIGZvbnQtd2VpZ2h0OiA2MDA7XG4gIGZvbnQtc2l6ZTogMTZweDtcbn0iXX0= */");

/***/ }),

/***/ "./src/app/pages/feed/feed.page.ts":
/*!*****************************************!*\
  !*** ./src/app/pages/feed/feed.page.ts ***!
  \*****************************************/
/*! exports provided: FeedPage */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "FeedPage", function() { return FeedPage; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js");
/* harmony import */ var _ionic_angular__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @ionic/angular */ "./node_modules/@ionic/angular/__ivy_ngcc__/fesm2015/ionic-angular.js");
/* harmony import */ var _services_student_service__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! ../../services/student.service */ "./src/app/services/student.service.ts");
/* harmony import */ var _student_model_student_model_page__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(/*! ../student-model/student-model.page */ "./src/app/pages/student-model/student-model.page.ts");





let FeedPage = class FeedPage {
    constructor(service, alertCtrl, modalCtrl) {
        this.service = service;
        this.alertCtrl = alertCtrl;
        this.modalCtrl = modalCtrl;
    }
    ngOnInit() {
        this.service.getAll().subscribe((response) => {
            this.students = response;
        });
    }
    addStudent() {
        // open modal
        this.modalCtrl
            .create({
            component: _student_model_student_model_page__WEBPACK_IMPORTED_MODULE_4__["StudentModelPage"],
        })
            .then((modal) => {
            modal.present();
            return modal.onDidDismiss();
        })
            .then(({ data, role }) => {
            if (role === "created") {
                this.students.push(data);
            }
        });
    }
    removeStudent(id) {
        this.alertCtrl
            .create({
            header: "Delete",
            message: "Are you sure you want to delete ? ",
            buttons: [
                {
                    text: "Yes",
                    handler: () => {
                        this.service.remove(id).subscribe(() => {
                            this.students = this.students.filter((std) => std.id !== id);
                        });
                    },
                },
                { text: "No", role: "cancel" },
            ],
        })
            .then((alertEl) => alertEl.present());
    }
    updatedStudent(student) {
        this.modalCtrl
            .create({
            component: _student_model_student_model_page__WEBPACK_IMPORTED_MODULE_4__["StudentModelPage"],
            componentProps: { student: student },
        })
            .then((modal) => {
            modal.present();
            return modal.onDidDismiss();
        })
            .then(({ data, role }) => {
            if (role === "updated") {
                this.students.filter((std) => {
                    if (data.id === std.id) {
                        return data;
                    }
                    return std;
                });
            }
        });
    }
};
FeedPage.ctorParameters = () => [
    { type: _services_student_service__WEBPACK_IMPORTED_MODULE_3__["StudentService"] },
    { type: _ionic_angular__WEBPACK_IMPORTED_MODULE_2__["AlertController"] },
    { type: _ionic_angular__WEBPACK_IMPORTED_MODULE_2__["ModalController"] }
];
FeedPage = Object(tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"])([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["Component"])({
        selector: "app-feed",
        template: Object(tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"])(__webpack_require__(/*! raw-loader!./feed.page.html */ "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/feed/feed.page.html")).default,
        styles: [Object(tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"])(__webpack_require__(/*! ./feed.page.scss */ "./src/app/pages/feed/feed.page.scss")).default]
    })
], FeedPage);



/***/ })

}]);
//# sourceMappingURL=pages-feed-feed-module-es2015.js.map