# Test_Project_HS_Application

 Test for Play Store Deployment

AMBA DIGITAL APP PROGRESS REPORT
Date 10/2/2022
-Finshing up on documenting the current application

-Creating a simple template to mirror the same functionality so as to be able to publish the application to IOS and Android Play Store

-Making technical inquisitions of all the Required-functionality to mirror on the Multi-platform version

-Checking and resolving all the API issues including the OTP sign-up module


Current Discussions
-Remaking the application to a more simpler version with the reuired functionality so as to be able to minimise the room for errors that cause the current application to fail

-What are the key functionalities that should be mirrored through to  the Multi-platform version

-Writing a comprehensive documentation to help in the future maintenance efforts of the application

CURRENT PROGRESS 
Date 14/10/2022

-Technical Project Documentation

-Tree Structure Code Analysis

-Code Review

-Code Refactoring Methodologies

PROJECT STRUCTURE

app

AndroidManifest.xml

hsmicrofinance

holders

BillsHolder

LocalDatabase

UserDao

UserDB

UserEntity

Network

data

Constants

LoansDescription

entity

AccountExtraInfoResponse

AddCommentSupportResponse

Banks

BanksCurrencyDetails

BankTransferHistory

Countries

Currencies

ForgotPasswordResponse

HSgroupTransfer

InternalTransferResponse

LoginResponse
OtherBankTransferDetails

OtherBankTransferResponse

OTPOtherBankResponse

PayLoanResponse

Person

PinChangeResponse

SingleSupportItem

SliderData

Status

SuccessfulTransfer

SupportHistory

SupportResponse

TransferSuccesful

UserAccountDetails

UserRegistrationDetails

UserRegResponse


UserVerificationetails

UserVerificationResponse

UserVerificationStatus

WithdrawDetails

models

AccountOtpConfirmation

AccountPasswordChange

AccountSettingConfirmation

AllUsers

Billing

BillPayment

Bills

BillStatement

CreditTransferDeposit

DashboardData

DepositHistory

DetailsForWithdraw

EdepositStatement

HSContacts

InvestmentHistory

InvestmentPlanDepositModel

InvestPlans

LoanHistories

LoanPack

LoanPlans

LoanRequest

ManualDeposit

ManualPaymentDetails

MpesaDepositCallBack

MpesaResponseBody

MpesaStatus

PaymentGateWays

PaymentRequest

PaymentResponse

PhoneNumbers

SubmitCreditDebitPayment

TransactionHistory

UpdateAccountInfo

UploadDetails

WithdrawDetail

WithDrawOTPResponse

WithrawOTPRequest

APIService

RetrofitInstance

TokenInteceptor

PermissionsHelper

FragmentPermissionInterface

PermissionsHelperFragment

StorageResultAccess

StorageResultAccessInterface

Services

MyFirebaseMessagingServiceClass

UI

adapters

BillHistoryAdapter

BillsAdapter
ContactsAdapter

ContactsOnHsAdapter

DepositHistoryAdapter

EDepositStatementAdapter

HSGroupAdapter

HsGroupTransferAdapter

InvestmentHistoryAdapter

InvestmentPackagesAdapter

LatestTransactionAdapter

LoanHistoryAdapter

LoanItemsAdapter

MpesaDepositAdapter

MpesaPendingAdapter

OtherBankTranferAdapter

PayLoansAdapter

RecyclerItemClickListener

SingleSupportItemAdapter

SliderAdapter

SupportItemsAdapter

ViewPagerAdapter

billing

AirtimeActivity

BankActivity

BillingActivity

ConfirmBillActivity

Controller

FcmMessageService

OtherBillActivity

PhoneBookActivity

StripeActivity

WebviewActivity

Fragments

AccountSettings

AccountSetting

BasicSettings

PasswordChange

UpdateSecurityCode

BasicDeposit

Credit

CreditDebit

CreditDebitPayment

CreditDebitPaymentSubmit

EDeposit

BasicEDeposit

HSPayments

HSPay

HSPayments

HSPaymentsSubmit

Mpesa

MobileMoney

MobileMoneyPayment

MpesaPendingDeposit

BasicDepositHistory

DepositHistorySingleItem

EdepositHistory

MpesaDepositHistory

StatementEdeposit

BasicInvestment

BasicInvestmentHistory

BasicInvestmentPackages

InvestmentPlansDeposit

SingleInvestmentHistory

BasicLoans

BasicLoanHistory

BasicLoanPackages

BasicPayLoans

LoanHistorySingleItem

MyLoans

PayLoanOTP

PayLoansDirectDeposit

RequestLoan

BasicPayForFriends

BasicPayfriends

Contacts

PayForFriendsOTPFragment


PayfriendsViaBank

PayFriendsViaMpesa

PayLoansViaMpesa

BasicTransfer

ExternalBankTransfer

OtherBankTransferFragment

OtherBankTransferOtpFragment

SingleOtherBankTransaction

StatementBankTransfer

InternalBankTransfer

InternalTransferOtpFragment

OwnBankTransferFragment

StatementGroupTransfer

TransferFundsFragment

BasicWithdraw

BasicWithdrawMoney

ConfirmTransfer

TranferOTPconfirm

Bills

BillHistory

BillRequestFragment

BillsRecieved

BillsTabs

CreateBill

SingleStatementBills

StatementBills

Login

BaseLogin

LoginFragment

Pins

PinLoginAccountSetting

PinLoginFragment

PinLoginViewModel

PinSetterAccountSetting

PinSetterFragment

PinSettterLogin

profile

AccountStatements

BasicAccount

Profile

Registration

RegisterFragment

RegisterPersonalInfo

RegSharedPref

SignUpFragment

TermsAndConditionsFragment

Support

AddSupportFragment

BasicSupport

ViewSupportItem

Transactions

BasicLatestTransactions

BasicTransactionHistory

SingleTransaction

UserVerification

UserVerificationFragment

BasicDashboard

Package

viewmodels

BaseLogin

ForgotPasswordActivity

HomeActivity

LoginActivity

MapsActivity

MyTimber

PackageActivity

SignUpActivity

SplashScreen

TermsAndConditionsActivity

hsmicrofinance

ExampleInstrumentedTest

hsmicrofinance

ExampleUnitTest

anim

bottom_up.xml

from_left.xml

from_right.xml

to_left.xml

to_right.xml

color

color.xml

drawable

drawable-mdpi

drawable-anydpi

drawable-xxhdpi

drawable-xhdpi

drawable-v24

drawable-hdpi

account.png

backarrow.xml

backarrow.png

backarrow.png

backarrow.png

backarrow.png

bills.png

bimaloans.png

bottom_nav_icon_selector.xml

bottom_nav_selector.xml

bt_uiborder.xml

bt_uisquare.xml

businessloan.png

cardback.xml

chamaloan.png

check_shape.xml

circle.xml

circlet.xml

circletransparent.xml

coin16.png

coin24.png

coin32.png

credit_pc.png

cursor.xml

dashroundcorners.xml

data_send.png

depohistory.png

deposit64.png

downloadicon.png

edeposit.png

edittext_background.xml

friends512.png

gold_ingots.png

grouptransfer.png

header.png

header_register.png

ic_account_dark.png

ic_account_dark.png

ic_account_dark.png

ic_account_dark.xml

ic_account_dark.png

ic_add.xml

ic_arrow.xml

ic_baseline_account_box_24.xml

ic_baseline_arrow_back_24.xml

ic_baseline_arrow_forward_ios_24.xml

ic_baseline_check_24.xml

ic_baseline_euro_24.xml

ic_baseline_flag_24.xml

ic_baseline_front_hand_24.xml

ic_baseline_history_transaction_24.xml

ic_baseline_house_24.xml

ic_baseline_live_help_24.xml

ic_basic_money_24.xml


ic_check_correct.xml

ic_delete.xml

ic_deposit_24.xml

ic_deposit_histroy_24.xml

ic_dollar_24.xml

ic_email_24.xml

ic_friendst_24.xml

ic_history_24.xml

ic_home.xml

ic_home_24.xml

ic_id_24.xml

ic_invest_dark.png

ic_invest_dark.xml

ic_invest_dark.png

ic_invest_dark.png

ic_invest_dark.png

ic_launcher_background.xml

ic_launcher_foreground.xml

ic_loan_history_24.xml

ic_loan_package_24.xml

ic_location_24.xml

ic_lock.xml

ic_lock_24.xml

ic_lock_open_24.xml

ic_logout_24.xml

ic_money_24.xml

ic_person.xml

ic_person_24.xml

ic_phone.xml

ic_search_24.xml

ic_settings_24.xml

ic_statement_24.xml

ic_support_24.xml

ic_withdraw_24.xml

img.webp

invest.png

investment512.png

investment64.png

kilimoloan.png

latest_transaction.jpg

lipanampesa.png

load.png

loan64.png


loanhistory512.png

loans.png

loansicon.png


logbookloan.png

login_background.xml

login_imageview_background.xml

logo.png

logo1.png

logofacebook.png


message_received_shape.xml

message_send_shape.xml

mobile_money.jpg

mobilemoney.jpg

money64.png

moneycard.png

moneytransfer512.png

moneytransfer64.png

mybills.png

notifybell.xml

pay.png

personloan.png

pibalance.png

piemail.png

piidcard.png

pin_failed_shape.xml

pin_input_shape.xml

pin_login_inner_shape.xml

pin_shape.xml

pin_verification_shape.xml

piname.png

pitelephone.png

platinum.png

round_basic_button.xml

round_edit_text.xml

rounded_gold_button.xml

rounded_premium_button.xml

selected.xml

send_icon.xml

sendsupport.png

show.xml

stackofcoins.png

standard.png

stars.png

support.png

titledeed.png

user.png

font

opensansregular.ttf

layout

activity_airtime.xml

activity_bank.xml

activity_base_login.xml

activity_billing.xml

activity_confirm_bill.xml

activity_forgot_password.xml

activity_home.xml

activity_login.xml

activity_maps.xml

activity_other_bill.xml

activity_package.xml

activity_phone_book.xml

activity_sign_up.xml

activity_splash_screen.xml

activity_stripe.xml

activity_terms_and_conditions.xml

activity_verification.xml

activity_webview.xml

basic_support_items.xml

bill_history_item.xml

bill_statement_item.xml

contact_item.xml

dailog_comming_soon.xml

deposit_history_items.xml

fragment_account_setting.xml

fragment_account_statements.xml

fragment_add_support.xml

fragment_base_login.xml

fragment_basic_account.xml

fragment_basic_dashboard.xml

fragment_basic_deposit_history.xml

fragment_basic_e_deposit.xml

fragment_basic_investment_history.xml

fragment_basic_investment_packages.xml

fragment_basic_latest_transactions.xml

fragment_basic_loan_history.xml

fragment_basic_loan_packages.xml

fragment_basic_pay_loans.xml

fragment_basic_payfriends.xml

fragment_basic_settings.xml

fragment_basic_support.xml

fragment_basic_transaction_history.xml

fragment_basic_withdraw_money.xml

fragment_bill_history.xml

fragment_bill_request.xml

fragment_bills_recieved.xml

fragment_bills_tabs.xml

fragment_confirm_transfer.xml

fragment_contacts.xml

fragment_create_bill.xml

fragment_credit_debit.xml

fragment_credit_debit_payment.xml

fragment_credit_debit_payment_submit.xml

fragment_deposit_history_single_item.xml

fragment_edeposit_history.xml

fragment_forgot_password.xml

fragment_h_s_pay.xml

fragment_h_s_payments.xml

fragment_h_s_payments_submit.xml

fragment_internal_transfer_otp.xml

fragment_loan_history_single_item.xml

fragment_login.xml

fragment_mobile_money.xml

fragment_mobile_money_payment.xml

fragment_mpesa_deposit_history.xml

fragment_mpesa_pending_deposit.xml

fragment_my_loans.xml

fragment_other_bank_transfer.xml

fragment_other_bank_transfer_otp.xml

fragment_own_bank_transfer.xml

fragment_password_change.xml

fragment_pay_for_friends_o_t_p.xml

fragment_pay_friends_via_mpesa.xml

fragment_pay_loan_o_t_p.xml

fragment_pay_loans_direct_deposit.xml

fragment_pay_loans_via_mpesa.xml

fragment_payfriends_via_bank.xml

fragment_pin_login.xml

fragment_pin_login_account_setting.xml

fragment_pin_setter.xml

fragment_pin_setter_account_setting.xml

fragment_pin_settter_login.xml

fragment_pinlock.xml

fragment_profile.xml

fragment_register.xml

fragment_register_personal_info.xml

fragment_request_loan.xml

fragment_sign_up.xml

fragment_single_investment_history.xml

fragment_single_other_bank_transaction.xml

fragment_single_statement_bills.xml

fragment_single_transaction.xml

fragment_statement_bank_transfer.xml

fragment_statement_bills.xml

fragment_statement_edeposit.xml

fragment_statement_group_transfer.xml

fragment_terms_and_conditions.xml

fragment_tranfer_o_t_pconfirm.xml

fragment_transfer_funds.xml

fragment_update_security_code.xml

fragment_user_loans_list.xml

fragment_user_verification.xml

fragment_view_support_item.xml

investhistoryitem.xml

investment_package_item.xml

investment_plan_deposit.xml

item_bill.xml

latest_transactions.xml

list_group.xml

list_item.xml

loanhistoryitem.xml

loanitemsdisplay.xml

mpesa_history_item.xml

mpesa_status_item.xml

nav_header.xml

other_bank_transfer_item.xml

packages.xml

pageblank.xml

slidable_image_item.xml

statement_edeposit_item.xml

statement_group_item.xml

support_receivedmessages_items.xml

supportmessage_item.xml

user_loan_items.xml

menu

basic_nav_drawer_menu.xml

bottom_nav_menu.xml

mipmap-xxxhdpi

mipmap-anydpi-v26

mipmap-xhdpi

mipmap-xxhdpi

mipmap-mdpi


mipmap-hdpi

ic_launcher.png

ic_launcher.png

ic_launcher.png

ic_launcher.png

ic_launcher.png

ic_launcher.xml

ic_launcher_round.png

ic_launcher_round.png

ic_launcher_round.xml

ic_launcher_round.png

ic_launcher_round.png

ic_launcher_round.png

logo_launcher.png

logo_launcher.png

logo_launcher.png

logo_launcher.png

logo_launcher.png

navigation

basic_nav_graph.xml

raw

bills.json

comming.json

notifications.json

profile.json

splash.json

values-night

values

values

colors.xml

dimens.xml

google_maps_api.xml

strings.xml

styles.xml

themes.xml

themes.xml

xml

provider_paths.xml

values

com_crashlytics_build_id.xml

build.gradle

build.gradle

gradle-wrapper.properties

proguard-rules.pro

gradle.properties

settings.gradle

local.properties
