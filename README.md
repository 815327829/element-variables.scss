# element-variables.scss
element-variables.scss 配置参数
#位于node_nodules/element-ui/packages/theme-chalk/src/common/var.scss


/* Element Chalk Variables */

// Special comment for theme configurator
// type|skipAutoTranslation|Category|Order
// skipAutoTranslation 1

/* Transition
-------------------------- */
$--all-transition: all .3s cubic-bezier(.645,.045,.355,1) !default;
$--fade-transition: opacity 300ms cubic-bezier(0.23, 1, 0.32, 1) !default;
$--fade-linear-transition: opacity 200ms linear !default;
$--md-fade-transition: transform 300ms cubic-bezier(0.23, 1, 0.32, 1), opacity 300ms cubic-bezier(0.23, 1, 0.32, 1) !default;
$--border-transition-base: border-color .2s cubic-bezier(.645,.045,.355,1) !default;
$--color-transition-base: color .2s cubic-bezier(.645,.045,.355,1) !default;

/* Color
-------------------------- */
/// color|1|Brand Color|0
$--color-primary: #409EFF !default;
/// color|1|Background Color|4
$--color-white: #FFFFFF !default;
/// color|1|Background Color|4
$--color-black: #000000 !default;
$--color-primary-light-1: mix($--color-white, $--color-primary, 10%) !default; /* 53a8ff */
$--color-primary-light-2: mix($--color-white, $--color-primary, 20%) !default; /* 66b1ff */
$--color-primary-light-3: mix($--color-white, $--color-primary, 30%) !default; /* 79bbff */
$--color-primary-light-4: mix($--color-white, $--color-primary, 40%) !default; /* 8cc5ff */
$--color-primary-light-5: mix($--color-white, $--color-primary, 50%) !default; /* a0cfff */
$--color-primary-light-6: mix($--color-white, $--color-primary, 60%) !default; /* b3d8ff */
$--color-primary-light-7: mix($--color-white, $--color-primary, 70%) !default; /* c6e2ff */
$--color-primary-light-8: mix($--color-white, $--color-primary, 80%) !default; /* d9ecff */
$--color-primary-light-9: mix($--color-white, $--color-primary, 90%) !default; /* ecf5ff */
/// color|1|Functional Color|1
$--color-success: #67C23A !default;
/// color|1|Functional Color|1
$--color-warning: #E6A23C !default;
/// color|1|Functional Color|1
$--color-danger: #F56C6C !default;
/// color|1|Functional Color|1
$--color-info: #909399 !default;

$--color-success-light: mix($--color-white, $--color-success, 80%) !default;
$--color-warning-light: mix($--color-white, $--color-warning, 80%) !default;
$--color-danger-light: mix($--color-white, $--color-danger, 80%) !default;
$--color-info-light: mix($--color-white, $--color-info, 80%) !default;

$--color-success-lighter: mix($--color-white, $--color-success, 90%) !default;
$--color-warning-lighter: mix($--color-white, $--color-warning, 90%) !default;
$--color-danger-lighter: mix($--color-white, $--color-danger, 90%) !default;
$--color-info-lighter: mix($--color-white, $--color-info, 90%) !default;
/// color|1|Font Color|2
$--color-text-primary: #303133 !default;
/// color|1|Font Color|2
$--color-text-regular: #606266 !default;
/// color|1|Font Color|2
$--color-text-secondary: #909399 !default;
/// color|1|Font Color|2
$--color-text-placeholder: #C0C4CC !default;
/// color|1|Border Color|3
$--border-color-base: #DCDFE6 !default;
/// color|1|Border Color|3
$--border-color-light: #E4E7ED !default;
/// color|1|Border Color|3
$--border-color-lighter: #EBEEF5 !default;
/// color|1|Border Color|3
$--border-color-extra-light: #F2F6FC !default;

// Background
/// color|1|Background Color|4
$--background-color-base: #F5F7FA !default;

/* Link
-------------------------- */
$--link-color: $--color-primary-light-2 !default;
$--link-hover-color: $--color-primary !default;

/* Border
-------------------------- */
$--border-width-base: 1px !default;
$--border-style-base: solid !default;
$--border-color-hover: $--color-text-placeholder !default;
$--border-base: $--border-width-base $--border-style-base $--border-color-base !default;
/// borderRadius|1|Radius|0
$--border-radius-base: 4px !default;
/// borderRadius|1|Radius|0
$--border-radius-small: 2px !default;
/// borderRadius|1|Radius|0
$--border-radius-circle: 100% !default;
/// borderRadius|1|Radius|0
$--border-radius-zero: 0 !default;

// Box-shadow
/// boxShadow|1|Shadow|1
$--box-shadow-base: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .04) !default;
// boxShadow|1|Shadow|1
$--box-shadow-dark: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .12) !default;
/// boxShadow|1|Shadow|1
$--box-shadow-light: 0 2px 12px 0 rgba(0, 0, 0, 0.1) !default;

/* Fill
-------------------------- */
$--fill-base: $--color-white !default;

/* Typography
-------------------------- */
$--font-path: 'fonts' !default;
$--font-display: 'auto' !default;
/// fontSize|1|Font Size|0
$--font-size-extra-large: 20px !default;
/// fontSize|1|Font Size|0
$--font-size-large: 18px !default;
/// fontSize|1|Font Size|0
$--font-size-medium: 16px !default;
/// fontSize|1|Font Size|0
$--font-size-base: 14px !default;
/// fontSize|1|Font Size|0
$--font-size-small: 13px !default;
/// fontSize|1|Font Size|0
$--font-size-extra-small: 12px !default;
/// fontWeight|1|Font Weight|1
$--font-weight-primary: 500 !default;
/// fontWeight|1|Font Weight|1
$--font-weight-secondary: 100 !default;
/// fontLineHeight|1|Line Height|2
$--font-line-height-primary: 24px !default;
/// fontLineHeight|1|Line Height|2
$--font-line-height-secondary: 16px !default;
$--font-color-disabled-base: #bbb !default;
/* Size
-------------------------- */
$--size-base: 14px !default;

/* z-index
-------------------------- */
$--index-normal: 1 !default;
$--index-top: 1000 !default;
$--index-popper: 2000 !default;

/* Disable base
-------------------------- */
$--disabled-fill-base: $--background-color-base !default;
$--disabled-color-base: $--color-text-placeholder !default;
$--disabled-border-base: $--border-color-light !default;

/* Icon
-------------------------- */
$--icon-color: #666 !default;
$--icon-color-base: $--color-info !default;

/* Checkbox
-------------------------- */
/// fontSize||Font|1
$--checkbox-font-size: 14px !default;
/// fontWeight||Font|1
$--checkbox-font-weight: $--font-weight-primary !default;
/// color||Color|0
$--checkbox-font-color: $--color-text-regular !default;
$--checkbox-input-height: 14px !default;
$--checkbox-input-width: 14px !default;
/// borderRadius||Border|2
$--checkbox-border-radius: $--border-radius-small !default;
/// color||Color|0
$--checkbox-background-color: $--color-white !default;
$--checkbox-input-border: $--border-base !default;

/// color||Color|0
$--checkbox-disabled-border-color: $--border-color-base !default;
$--checkbox-disabled-input-fill: #edf2fc !default;
$--checkbox-disabled-icon-color: $--color-text-placeholder !default;

$--checkbox-disabled-checked-input-fill: $--border-color-extra-light !default;
$--checkbox-disabled-checked-input-border-color: $--border-color-base !default;
$--checkbox-disabled-checked-icon-color: $--color-text-placeholder !default;

/// color||Color|0
$--checkbox-checked-font-color: $--color-primary !default;
$--checkbox-checked-input-border-color: $--color-primary !default;
/// color||Color|0
$--checkbox-checked-background-color: $--color-primary !default;
$--checkbox-checked-icon-color: $--fill-base !default;

$--checkbox-input-border-color-hover: $--color-primary !default;
/// height||Other|4
$--checkbox-bordered-height: 40px !default;
/// padding||Spacing|3
$--checkbox-bordered-padding: 9px 20px 9px 10px !default;
/// padding||Spacing|3
$--checkbox-bordered-medium-padding: 7px 20px 7px 10px !default;
/// padding||Spacing|3
$--checkbox-bordered-small-padding: 5px 15px 5px 10px !default;
/// padding||Spacing|3
$--checkbox-bordered-mini-padding: 3px 15px 3px 10px !default;
$--checkbox-bordered-medium-input-height: 14px !default;
$--checkbox-bordered-medium-input-width: 14px !default;
/// height||Other|4
$--checkbox-bordered-medium-height: 36px !default;
$--checkbox-bordered-small-input-height: 12px !default;
$--checkbox-bordered-small-input-width: 12px !default;
/// height||Other|4
$--checkbox-bordered-small-height: 32px !default;
$--checkbox-bordered-mini-input-height: 12px !default;
$--checkbox-bordered-mini-input-width: 12px !default;
/// height||Other|4
$--checkbox-bordered-mini-height: 28px !default;

/// color||Color|0
$--checkbox-button-checked-background-color: $--color-primary !default;
/// color||Color|0
$--checkbox-button-checked-font-color: $--color-white !default;
/// color||Color|0
$--checkbox-button-checked-border-color: $--color-primary !default;



/* Radio
-------------------------- */
/// fontSize||Font|1
$--radio-font-size: $--font-size-base !default;
/// fontWeight||Font|1
$--radio-font-weight: $--font-weight-primary !default;
/// color||Color|0
$--radio-font-color: $--color-text-regular !default;
$--radio-input-height: 14px !default;
$--radio-input-width: 14px !default;
/// borderRadius||Border|2
$--radio-input-border-radius: $--border-radius-circle !default;
/// color||Color|0
$--radio-input-background-color: $--color-white !default;
$--radio-input-border: $--border-base !default;
/// color||Color|0
$--radio-input-border-color: $--border-color-base !default;
/// color||Color|0
$--radio-icon-color: $--color-white !default;

$--radio-disabled-input-border-color: $--disabled-border-base !default;
$--radio-disabled-input-fill: $--disabled-fill-base !default;
$--radio-disabled-icon-color: $--disabled-fill-base !default;

$--radio-disabled-checked-input-border-color: $--disabled-border-base !default;
$--radio-disabled-checked-input-fill: $--disabled-fill-base !default;
$--radio-disabled-checked-icon-color: $--color-text-placeholder !default;

/// color||Color|0
$--radio-checked-font-color: $--color-primary !default;
/// color||Color|0
$--radio-checked-input-border-color: $--color-primary !default;
/// color||Color|0
$--radio-checked-input-background-color: $--color-white !default;
/// color||Color|0
$--radio-checked-icon-color: $--color-primary !default;

$--radio-input-border-color-hover: $--color-primary !default;

$--radio-bordered-height: 40px !default;
$--radio-bordered-padding: 12px 20px 0 10px !default;
$--radio-bordered-medium-padding: 10px 20px 0 10px !default;
$--radio-bordered-small-padding: 8px 15px 0 10px !default;
$--radio-bordered-mini-padding: 6px 15px 0 10px !default;
$--radio-bordered-medium-input-height: 14px !default;
$--radio-bordered-medium-input-width: 14px !default;
$--radio-bordered-medium-height: 36px !default;
$--radio-bordered-small-input-height: 12px !default;
$--radio-bordered-small-input-width: 12px !default;
$--radio-bordered-small-height: 32px !default;
$--radio-bordered-mini-input-height: 12px !default;
$--radio-bordered-mini-input-width: 12px !default;
$--radio-bordered-mini-height: 28px !default;

/// fontSize||Font|1
$--radio-button-font-size: $--font-size-base !default;
/// color||Color|0
$--radio-button-checked-background-color: $--color-primary !default;
/// color||Color|0
$--radio-button-checked-font-color: $--color-white !default;
/// color||Color|0
$--radio-button-checked-border-color: $--color-primary !default;
$--radio-button-disabled-checked-fill: $--border-color-extra-light !default;

/* Select
-------------------------- */
$--select-border-color-hover: $--border-color-hover !default;
$--select-disabled-border: $--disabled-border-base !default;
/// fontSize||Font|1
$--select-font-size: $--font-size-base !default;
$--select-close-hover-color: $--color-text-secondary !default;

$--select-input-color: $--color-text-placeholder !default;
$--select-multiple-input-color: #666 !default;
/// color||Color|0
$--select-input-focus-border-color: $--color-primary !default;
/// fontSize||Font|1
$--select-input-font-size: 14px !default;

$--select-option-color: $--color-text-regular !default;
$--select-option-disabled-color: $--color-text-placeholder !default;
$--select-option-disabled-background: $--color-white !default;
/// height||Other|4
$--select-option-height: 34px !default;
$--select-option-hover-background: $--background-color-base !default;
/// color||Color|0
$--select-option-selected-font-color: $--color-primary !default;
$--select-option-selected-hover: $--background-color-base !default;

$--select-group-color: $--color-info !default;
$--select-group-height: 30px !default;
$--select-group-font-size: 12px !default;

$--select-dropdown-background: $--color-white !default;
$--select-dropdown-shadow: $--box-shadow-light !default;
$--select-dropdown-empty-color: #999 !default;
/// height||Other|4
$--select-dropdown-max-height: 274px !default;
$--select-dropdown-padding: 6px 0 !default;
$--select-dropdown-empty-padding: 10px 0 !default;
$--select-dropdown-border: solid 1px $--border-color-light !default;

/* Alert
-------------------------- */
$--alert-padding: 8px 16px !default;
/// borderRadius||Border|2
$--alert-border-radius: $--border-radius-base !default;
/// fontSize||Font|1
$--alert-title-font-size: 13px !default;
/// fontSize||Font|1
$--alert-description-font-size: 12px !default;
/// fontSize||Font|1
$--alert-close-font-size: 12px !default;
/// fontSize||Font|1
$--alert-close-customed-font-size: 13px !default;

$--alert-success-color: $--color-success-lighter !default;
$--alert-info-color: $--color-info-lighter !default;
$--alert-warning-color: $--color-warning-lighter !default;
$--alert-danger-color: $--color-danger-lighter !default;

/// height||Other|4
$--alert-icon-size: 16px !default;
/// height||Other|4
$--alert-icon-large-size: 28px !default;

/* MessageBox
-------------------------- */
/// color||Color|0
$--messagebox-title-color: $--color-text-primary !default;
$--msgbox-width: 420px !default;
$--msgbox-border-radius: 4px !default;
/// fontSize||Font|1
$--messagebox-font-size: $--font-size-large !default;
/// fontSize||Font|1
$--messagebox-content-font-size: $--font-size-base !default;
/// color||Color|0
$--messagebox-content-color: $--color-text-regular !default;
/// fontSize||Font|1
$--messagebox-error-font-size: 12px !default;
$--msgbox-padding-primary: 15px !default;
/// color||Color|0
$--messagebox-success-color: $--color-success !default;
/// color||Color|0
$--messagebox-info-color: $--color-info !default;
/// color||Color|0
$--messagebox-warning-color: $--color-warning !default;
/// color||Color|0
$--messagebox-danger-color: $--color-danger !default;

/* Message
-------------------------- */
$--message-shadow: $--box-shadow-base !default;
$--message-min-width: 380px !default;
$--message-background-color: #edf2fc !default;
$--message-padding: 15px 15px 15px 20px !default;
/// color||Color|0
$--message-close-icon-color: $--color-text-placeholder !default;
/// height||Other|4
$--message-close-size: 16px !default;
/// color||Color|0
$--message-close-hover-color: $--color-text-secondary !default;

/// color||Color|0
$--message-success-font-color: $--color-success !default;
/// color||Color|0
$--message-info-font-color: $--color-info !default;
/// color||Color|0
$--message-warning-font-color: $--color-warning !default;
/// color||Color|0
$--message-danger-font-color: $--color-danger !default;

/* Notification
-------------------------- */
$--notification-width: 330px !default;
/// padding||Spacing|3
$--notification-padding: 14px 26px 14px 13px !default;
$--notification-radius: 8px !default;
$--notification-shadow: $--box-shadow-light !default;
/// color||Color|0
$--notification-border-color: $--border-color-lighter !default;
$--notification-icon-size: 24px !default;
$--notification-close-font-size: $--message-close-size !default;
$--notification-group-margin-left: 13px !default;
$--notification-group-margin-right: 8px !default;
/// fontSize||Font|1
$--notification-content-font-size: $--font-size-base !default;
/// color||Color|0
$--notification-content-color: $--color-text-regular !default;
/// fontSize||Font|1
$--notification-title-font-size: 16px !default;
/// color||Color|0
$--notification-title-color: $--color-text-primary !default;

/// color||Color|0
$--notification-close-color: $--color-text-secondary !default;
/// color||Color|0
$--notification-close-hover-color: $--color-text-regular !default;

/// color||Color|0
$--notification-success-icon-color: $--color-success !default;
/// color||Color|0
$--notification-info-icon-color: $--color-info !default;
/// color||Color|0
$--notification-warning-icon-color: $--color-warning !default;
/// color||Color|0
$--notification-danger-icon-color: $--color-danger !default;

/* Input
-------------------------- */
$--input-font-size: $--font-size-base !default;
/// color||Color|0
$--input-font-color: $--color-text-regular !default;
/// height||Other|4
$--input-height: 40px !default;
$--input-border: $--border-base !default;
$--input-border-color: $--border-color-base !default;
/// borderRadius||Border|2
$--input-border-radius: $--border-radius-base !default;
$--input-border-color-hover: $--border-color-hover !default;
/// color||Color|0
$--input-background-color: $--color-white !default;
$--input-fill-disabled: $--disabled-fill-base !default;
$--input-color-disabled: $--font-color-disabled-base !default;
/// color||Color|0
$--input-icon-color: $--color-text-placeholder !default;
/// color||Color|0
$--input-placeholder-color: $--color-text-placeholder !default;
$--input-max-width: 314px !default;

$--input-hover-border: $--border-color-hover !default;
$--input-clear-hover-color: $--color-text-secondary !default;

$--input-focus-border: $--color-primary !default;
$--input-focus-fill: $--color-white !default;

$--input-disabled-fill: $--disabled-fill-base !default;
$--input-disabled-border: $--disabled-border-base !default;
$--input-disabled-color: $--disabled-color-base !default;
$--input-disabled-placeholder-color: $--color-text-placeholder !default;

/// fontSize||Font|1
$--input-medium-font-size: 14px !default;
/// height||Other|4
$--input-medium-height: 36px !default;
/// fontSize||Font|1
$--input-small-font-size: 13px !default;
/// height||Other|4
$--input-small-height: 32px !default;
/// fontSize||Font|1
$--input-mini-font-size: 12px !default;
/// height||Other|4
$--input-mini-height: 28px !default;

/* Cascader
-------------------------- */
/// color||Color|0
$--cascader-menu-font-color: $--color-text-regular !default;
/// color||Color|0
$--cascader-menu-selected-font-color: $--color-primary !default;
$--cascader-menu-fill: $--fill-base !default;
$--cascader-menu-font-size: $--font-size-base !default;
$--cascader-menu-radius: $--border-radius-base !default;
$--cascader-menu-border: solid 1px $--border-color-light !default;
$--cascader-menu-shadow: $--box-shadow-light !default;
$--cascader-node-background-hover: $--background-color-base !default;
$--cascader-node-color-disabled:$--color-text-placeholder !default;
$--cascader-color-empty:$--color-text-placeholder !default;
$--cascader-tag-background: #f0f2f5;

/* Group
-------------------------- */
$--group-option-flex: 0 0 (1/5) * 100% !default;
$--group-option-offset-bottom: 12px !default;
$--group-option-fill-hover: rgba($--color-black, 0.06) !default;
$--group-title-color: $--color-black !default;
$--group-title-font-size: $--font-size-base !default;
$--group-title-width: 66px !default;

/* Tab
-------------------------- */
$--tab-font-size: $--font-size-base !default;
$--tab-border-line: 1px solid #e4e4e4 !default;
$--tab-header-color-active: $--color-text-secondary !default;
$--tab-header-color-hover: $--color-text-regular !default;
$--tab-header-color: $--color-text-regular !default;
$--tab-header-fill-active: rgba($--color-black, 0.06) !default;
$--tab-header-fill-hover: rgba($--color-black, 0.06) !default;
$--tab-vertical-header-width: 90px !default;
$--tab-vertical-header-count-color: $--color-white !default;
$--tab-vertical-header-count-fill: $--color-text-secondary !default;

/* Button
-------------------------- */
/// fontSize||Font|1
$--button-font-size: $--font-size-base !default;
/// fontWeight||Font|1
$--button-font-weight: $--font-weight-primary !default;
/// borderRadius||Border|2
$--button-border-radius: $--border-radius-base !default;
/// padding||Spacing|3
$--button-padding-vertical: 12px !default;
/// padding||Spacing|3
$--button-padding-horizontal: 20px !default;

/// fontSize||Font|1
$--button-medium-font-size: $--font-size-base !default;
/// borderRadius||Border|2
$--button-medium-border-radius: $--border-radius-base !default;
/// padding||Spacing|3
$--button-medium-padding-vertical: 10px !default;
/// padding||Spacing|3
$--button-medium-padding-horizontal: 20px !default;

/// fontSize||Font|1
$--button-small-font-size: 12px !default;
$--button-small-border-radius: #{$--border-radius-base - 1} !default;
/// padding||Spacing|3
$--button-small-padding-vertical: 9px !default;
/// padding||Spacing|3
$--button-small-padding-horizontal: 15px !default;
/// fontSize||Font|1
$--button-mini-font-size: 12px !default;
$--button-mini-border-radius: #{$--border-radius-base - 1} !default;
/// padding||Spacing|3
$--button-mini-padding-vertical: 7px !default;
/// padding||Spacing|3
$--button-mini-padding-horizontal: 15px !default;

/// color||Color|0
$--button-default-font-color: $--color-text-regular !default;
/// color||Color|0
$--button-default-background-color: $--color-white !default;
/// color||Color|0
$--button-default-border-color: $--border-color-base !default;

/// color||Color|0
$--button-disabled-font-color: $--color-text-placeholder !default;
/// color||Color|0
$--button-disabled-background-color: $--color-white !default;
/// color||Color|0
$--button-disabled-border-color: $--border-color-lighter !default;

/// color||Color|0
$--button-primary-border-color: $--color-primary !default;
/// color||Color|0
$--button-primary-font-color: $--color-white !default;
/// color||Color|0
$--button-primary-background-color: $--color-primary !default;
/// color||Color|0
$--button-success-border-color: $--color-success !default;
/// color||Color|0
$--button-success-font-color: $--color-white !default;
/// color||Color|0
$--button-success-background-color: $--color-success !default;
/// color||Color|0
$--button-warning-border-color: $--color-warning !default;
/// color||Color|0
$--button-warning-font-color: $--color-white !default;
/// color||Color|0
$--button-warning-background-color: $--color-warning !default;
/// color||Color|0
$--button-danger-border-color: $--color-danger !default;
/// color||Color|0
$--button-danger-font-color: $--color-white !default;
/// color||Color|0
$--button-danger-background-color: $--color-danger !default;
/// color||Color|0
$--button-info-border-color: $--color-info !default;
/// color||Color|0
$--button-info-font-color: $--color-white !default;
/// color||Color|0
$--button-info-background-color: $--color-info !default;

$--button-hover-tint-percent: 20% !default;
$--button-active-shade-percent: 10% !default;


/* cascader
-------------------------- */
$--cascader-height: 200px !default;

/* Switch
-------------------------- */
/// color||Color|0
$--switch-on-color: $--color-primary !default;
/// color||Color|0
$--switch-off-color: $--border-color-base !default;
/// fontSize||Font|1
$--switch-font-size: $--font-size-base !default;
$--switch-core-border-radius: 10px !default;
// height||Other|4 TODO: width 代码写死的40px 所以下面这三个属性都没意义
$--switch-width: 40px !default;
// height||Other|4
$--switch-height: 20px !default;
// height||Other|4
$--switch-button-size: 16px !default;

/* Dialog
-------------------------- */
$--dialog-background-color: $--color-white !default;
$--dialog-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.3) !default;
/// fontSize||Font|1
$--dialog-title-font-size: $--font-size-large !default;
/// fontSize||Font|1
$--dialog-content-font-size: 14px !default;
/// fontLineHeight||LineHeight|2
$--dialog-font-line-height: $--font-line-height-primary !default;
/// padding||Spacing|3
$--dialog-padding-primary: 20px !default;

/* Table
-------------------------- */
/// color||Color|0
$--table-border-color: $--border-color-lighter !default;
$--table-border: 1px solid $--table-border-color !default;
/// color||Color|0
$--table-font-color: $--color-text-regular !default;
/// color||Color|0
$--table-header-font-color: $--color-text-secondary !default;
/// color||Color|0
$--table-row-hover-background-color: $--background-color-base !default;
$--table-current-row-background-color: $--color-primary-light-9 !default;
/// color||Color|0
$--table-header-background-color: $--color-white !default;
$--table-fixed-box-shadow: 0 0 10px rgba(0, 0, 0, .12) !default;

/* Pagination
-------------------------- */
/// fontSize||Font|1
$--pagination-font-size: 13px !default;
/// color||Color|0
$--pagination-background-color: $--color-white !default;
/// color||Color|0
$--pagination-font-color: $--color-text-primary !default;
$--pagination-border-radius: 3px !default;
/// color||Color|0
$--pagination-button-color: $--color-text-primary !default;
/// height||Other|4
$--pagination-button-width: 35.5px !default;
/// height||Other|4
$--pagination-button-height: 28px !default;
/// color||Color|0
$--pagination-button-disabled-color: $--color-text-placeholder !default;
/// color||Color|0
$--pagination-button-disabled-background-color: $--color-white !default;
/// color||Color|0
$--pagination-hover-color: $--color-primary !default;

/* Popup
-------------------------- */
/// color||Color|0
$--popup-modal-background-color: $--color-black !default;
/// opacity||Other|1
$--popup-modal-opacity: 0.5 !default;

/* Popover
-------------------------- */
/// color||Color|0
$--popover-background-color: $--color-white !default;
/// fontSize||Font|1
$--popover-font-size: $--font-size-base !default;
/// color||Color|0
$--popover-border-color: $--border-color-lighter !default;
$--popover-arrow-size: 6px !default;
/// padding||Spacing|3
$--popover-padding: 12px !default;
$--popover-padding-large: 18px 20px !default;
/// fontSize||Font|1
$--popover-title-font-size: 16px !default;
/// color||Color|0
$--popover-title-font-color: $--color-text-primary !default;

/* Tooltip
-------------------------- */
/// color|1|Color|0
$--tooltip-fill: $--color-text-primary !default;
/// color|1|Color|0
$--tooltip-color: $--color-white !default;
/// fontSize||Font|1
$--tooltip-font-size: 12px !default;
/// color||Color|0
$--tooltip-border-color: $--color-text-primary !default;
$--tooltip-arrow-size: 6px !default;
/// padding||Spacing|3
$--tooltip-padding: 10px !default;

/* Tag
-------------------------- */
/// color||Color|0
$--tag-info-color: $--color-info !default;
/// color||Color|0
$--tag-primary-color: $--color-primary !default;
/// color||Color|0
$--tag-success-color: $--color-success !default;
/// color||Color|0
$--tag-warning-color: $--color-warning !default;
/// color||Color|0
$--tag-danger-color: $--color-danger !default;
/// fontSize||Font|1
$--tag-font-size: 12px !default;
$--tag-border-radius: 4px !default;
$--tag-padding: 0 10px !default;

/* Tree
-------------------------- */
/// color||Color|0
$--tree-node-hover-background-color: $--background-color-base !default;
/// color||Color|0
$--tree-font-color: $--color-text-regular !default;
/// color||Color|0
$--tree-expand-icon-color: $--color-text-placeholder !default;

/* Dropdown
-------------------------- */
$--dropdown-menu-box-shadow: $--box-shadow-light !default;
$--dropdown-menuItem-hover-fill: $--color-primary-light-9 !default;
$--dropdown-menuItem-hover-color: $--link-color !default;

/* Badge
-------------------------- */
/// color||Color|0
$--badge-background-color: $--color-danger !default;
$--badge-radius: 10px !default;
/// fontSize||Font|1
$--badge-font-size: 12px !default;
/// padding||Spacing|3
$--badge-padding: 6px !default;
/// height||Other|4
$--badge-size: 18px !default;

/* Card
--------------------------*/
/// color||Color|0
$--card-border-color: $--border-color-lighter !default;
$--card-border-radius: 4px !default;
/// padding||Spacing|3
$--card-padding: 20px !default;

/* Slider
--------------------------*/
/// color||Color|0
$--slider-main-background-color: $--color-primary !default;
/// color||Color|0
$--slider-runway-background-color: $--border-color-light !default;
$--slider-button-hover-color: mix($--color-primary, black, 97%) !default;
$--slider-stop-background-color: $--color-white !default;
$--slider-disable-color: $--color-text-placeholder !default;
$--slider-margin: 16px 0 !default;
$--slider-border-radius: 3px !default;
/// height|1|Other|4
$--slider-height: 6px !default;
/// height||Other|4
$--slider-button-size: 16px !default;
$--slider-button-wrapper-size: 36px !default;
$--slider-button-wrapper-offset: -15px !default;

/* Steps
--------------------------*/
$--steps-border-color: $--disabled-border-base !default;
$--steps-border-radius: 4px !default;
$--steps-padding: 20px !default;

/* Menu
--------------------------*/
/// fontSize||Font|1
$--menu-item-font-size: $--font-size-base !default;
/// color||Color|0
$--menu-item-font-color: $--color-text-primary !default;
/// color||Color|0
$--menu-background-color: $--color-white !default;
$--menu-item-hover-fill: $--color-primary-light-9 !default;

/* Rate
--------------------------*/
$--rate-height: 20px !default;
/// fontSize||Font|1
$--rate-font-size: $--font-size-base !default;
/// height||Other|3
$--rate-icon-size: 18px !default;
/// margin||Spacing|2
$--rate-icon-margin: 6px !default;
$--rate-icon-color: $--color-text-placeholder !default;

/* DatePicker
--------------------------*/
$--datepicker-font-color: $--color-text-regular !default;
/// color|1|Color|0
$--datepicker-off-font-color: $--color-text-placeholder !default;
/// color||Color|0
$--datepicker-header-font-color: $--color-text-regular !default;
$--datepicker-icon-color: $--color-text-primary !default;
$--datepicker-border-color: $--disabled-border-base !default;
$--datepicker-inner-border-color: #e4e4e4 !default;
/// color||Color|0
$--datepicker-inrange-background-color: $--border-color-extra-light !default;
/// color||Color|0
$--datepicker-inrange-hover-background-color: $--border-color-extra-light !default;
/// color||Color|0
$--datepicker-active-color: $--color-primary !default;
/// color||Color|0
$--datepicker-hover-font-color: $--color-primary !default;
$--datepicker-cell-hover-color: #fff !default;

/* Loading
--------------------------*/
/// height||Other|4
$--loading-spinner-size: 42px !default;
/// height||Other|4
$--loading-fullscreen-spinner-size: 50px !default;

/* Scrollbar
--------------------------*/
$--scrollbar-background-color: rgba($--color-text-secondary, .3) !default;
$--scrollbar-hover-background-color: rgba($--color-text-secondary, .5) !default;

/* Carousel
--------------------------*/
/// fontSize||Font|1
$--carousel-arrow-font-size: 12px !default;
$--carousel-arrow-size: 36px !default;
$--carousel-arrow-background: rgba(31, 45, 61, 0.11) !default;
$--carousel-arrow-hover-background: rgba(31, 45, 61, 0.23) !default;
/// width||Other|4
$--carousel-indicator-width: 30px !default;
/// height||Other|4
$--carousel-indicator-height: 2px !default;
$--carousel-indicator-padding-horizontal: 4px !default;
$--carousel-indicator-padding-vertical: 12px !default;
$--carousel-indicator-out-color: $--border-color-hover !default;

/* Collapse
--------------------------*/
/// color||Color|0
$--collapse-border-color: $--border-color-lighter !default;
/// height||Other|4
$--collapse-header-height: 48px !default;
/// color||Color|0
$--collapse-header-background-color: $--color-white !default;
/// color||Color|0
$--collapse-header-font-color: $--color-text-primary !default;
/// fontSize||Font|1
$--collapse-header-font-size: 13px !default;
/// color||Color|0
$--collapse-content-background-color: $--color-white !default;
/// fontSize||Font|1
$--collapse-content-font-size: 13px !default;
/// color||Color|0
$--collapse-content-font-color: $--color-text-primary !default;

/* Transfer
--------------------------*/
$--transfer-border-color: $--border-color-lighter !default;
$--transfer-border-radius: $--border-radius-base !default;
/// height||Other|4
$--transfer-panel-width: 200px !default;
/// height||Other|4
$--transfer-panel-header-height: 40px !default;
/// color||Color|0
$--transfer-panel-header-background-color: $--background-color-base !default;
/// height||Other|4
$--transfer-panel-footer-height: 40px !default;
/// height||Other|4
$--transfer-panel-body-height: 246px !default;
/// height||Other|4
$--transfer-item-height: 30px !default;
/// height||Other|4
$--transfer-filter-height: 32px !default;

/* Header
  --------------------------*/
$--header-padding: 0 20px !default;

/* Footer
--------------------------*/
$--footer-padding: 0 20px !default;

/* Main
--------------------------*/
$--main-padding: 20px !default;

/* Timeline
--------------------------*/
$--timeline-node-size-normal: 12px !default;
$--timeline-node-size-large: 14px !default;
$--timeline-node-color: $--border-color-light !default;

/* Backtop
--------------------------*/
/// color||Color|0
$--backtop-background-color: $--color-white !default;
/// color||Color|0
$--backtop-font-color: $--color-primary !default;
/// color||Color|0
$--backtop-hover-background-color: $--border-color-extra-light !default;

/* Link
--------------------------*/
/// fontSize||Font|1
$--link-font-size: $--font-size-base !default;
/// fontWeight||Font|1
$--link-font-weight: $--font-weight-primary !default;
/// color||Color|0
$--link-default-font-color: $--color-text-regular !default;
/// color||Color|0
$--link-default-active-color: $--color-primary !default;
/// color||Color|0
$--link-disabled-font-color: $--color-text-placeholder !default;
/// color||Color|0
$--link-primary-font-color: $--color-primary !default;
/// color||Color|0
$--link-success-font-color: $--color-success !default;
/// color||Color|0
$--link-warning-font-color: $--color-warning !default;
/// color||Color|0
$--link-danger-font-color: $--color-danger !default;
/// color||Color|0
$--link-info-font-color: $--color-info !default;
/* Calendar
--------------------------*/
/// border||Other|4
$--calendar-border: $--table-border !default;
/// color||Other|4
$--calendar-selected-background-color: #F2F8FE !default;
$--calendar-cell-width: 85px !default;

/* Form
-------------------------- */
/// fontSize||Font|1
$--form-label-font-size: $--font-size-base !default;

/* Avatar
--------------------------*/
/// color||Color|0
$--avatar-font-color: #fff !default;
/// color||Color|0
$--avatar-background-color: #C0C4CC !default;
/// fontSize||Font Size|1
$--avatar-text-font-size: 14px !default;
/// fontSize||Font Size|1
$--avatar-icon-font-size: 18px !default;
/// borderRadius||Border|2
$--avatar-border-radius: $--border-radius-base !default;
/// size|1|Avatar Size|3
$--avatar-large-size: 40px !default;
/// size|1|Avatar Size|3
$--avatar-medium-size: 36px !default;
/// size|1|Avatar Size|3
$--avatar-small-size: 28px !default;

/* Empty
-------------------------- */
$--empty-padding: 40px 0 !default;
$--empty-image-width: 160px !default;
$--empty-description-margin-top: 20px !default;
$--empty-bottom-margin-top: 20px !default;

/* Descriptions
-------------------------- */
$--descriptions-header-margin-bottom: 20px !default;
$--descriptions-title-font-size: 16px !default;
$--descriptions-table-border: 1px solid $--border-color-lighter !default;
$--descriptions-item-bordered-label-background: #fafafa !default;

/* Skeleton 
--------------------------*/
$--skeleton-color: #f2f2f2 !default;
$--skeleton-to-color: #e6e6e6 !default;

/* Svg
--------------- */
$--svg-monochrome-grey: #DCDDE0 !default;

/* Result
-------------------------- */
$--result-padding: 40px 30px !default;
$--result-icon-font-size: 64px !default;
$--result-title-font-size: 20px !default;
$--result-title-margin-top: 20px !default;
$--result-subtitle-margin-top: 10px !default;
$--result-extra-margin-top: 30px !default;
$--result-info-color: $--color-info !default;
$--result-success-color: $--color-success !default;
$--result-warning-color: $--color-warning !default;
$--result-danger-color: $--color-danger !default;

/* Break-point
--------------------------*/
$--sm: 768px !default;
$--md: 992px !default;
$--lg: 1200px !default;
$--xl: 1920px !default;

$--breakpoints: (
  'xs' : (max-width: $--sm - 1),
  'sm' : (min-width: $--sm),
  'md' : (min-width: $--md),
  'lg' : (min-width: $--lg),
  'xl' : (min-width: $--xl)
);

$--breakpoints-spec: (
  'xs-only' : (max-width: $--sm - 1),
  'sm-and-up' : (min-width: $--sm),
  'sm-only': "(min-width: #{$--sm}) and (max-width: #{$--md - 1})",
  'sm-and-down': (max-width: $--md - 1),
  'md-and-up' : (min-width: $--md),
  'md-only': "(min-width: #{$--md}) and (max-width: #{$--lg - 1})",
  'md-and-down': (max-width: $--lg - 1),
  'lg-and-up' : (min-width: $--lg),
  'lg-only': "(min-width: #{$--lg}) and (max-width: #{$--xl - 1})",
  'lg-and-down': (max-width: $--xl - 1),
  'xl-only' : (min-width: $--xl),
);
