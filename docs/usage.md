# Usage Guide / 使用說明

## 繁體中文

### 必填欄位

請放入以下欄位：

- Task：要顯示在日曆甘特圖中的任務、活動、專案項目或列標籤。

### 選填分類欄位

你可以視需求放入：

- Color Category：依分類分組，並用於圖例顯示。
- Bar Label Before Time：顯示在長條前方的文字。
- Bar Label After Time：顯示在長條後方的文字。
- Tooltips：顯示在 hover 提示中的額外補充欄位，可放入多個欄位。

### 時間區間欄位

此 visual 最多支援三組時間區間：

- Time Start 1
- Time End 1
- Time Start 2
- Time End 2
- Time Start 3
- Time End 3

每組時間區間應使用 Power BI 可辨識的日期或日期時間值。開始時間與結束時間應代表同一段排程。

### 格式設定

#### Labels

- Time 1 Label
- Time 2 Label
- Time 3 Label
- Legend Title

#### Bar Label Style

- Font Size
- Font Weight
- Font Family
- Font Color

#### Layout

- Week Height
- Bar Stack Mode
- Time 1 Height
- Time 2 Height
- Time 3 Height
- Time 1 Opacity
- Time 2 Opacity
- Time 3 Opacity
- Time 1 Radius
- Time 2 Radius
- Time 3 Radius

### Tooltips 額外資訊

預設 hover 內容會透過 Power BI 官方 tooltip 顯示任務、分類、時間區間、開始時間與結束時間。Tooltips 欄位用來補充使用者還想看的其他資料，例如負責人、狀態、部門、備註或進度。

### Bar Stack Mode

使用 Bar Stack Mode 控制長條排列方式：

- 0：Separate，分開顯示
- 1：Overlay by task，依任務重疊
- 2：Overlay all，全部重疊

### 常見問題

如果沒有顯示長條，請確認：

- Task 欄位有資料。
- 至少有一組開始/結束時間。
- 開始與結束值是有效的日期或日期時間。
- visual 的畫面大小足夠顯示日曆版面。

如果標籤不容易閱讀，可以調整：

- Font Size
- Font Color
- 時間區間透明度
- 長條高度

### 高對比模式

當 Power BI 啟用高對比模式時，visual 會使用 Power BI 提供的前景色、背景色與邊框色，避免使用一般模式中的彩色配置。

### 分類色彩

一般模式下，Color Category 的分類色彩會使用 Power BI 提供的色盤。這可讓 visual 更符合報表主題與 Power BI 的預設配色行為。

### Landing Page

當 visual 尚未放入必要欄位，或沒有有效時間資料時，畫面會顯示中英雙語提示，協助使用者知道需要加入哪些欄位或如何修正日期資料。

### 語系

visual 提供 en-US 與 zh-TW 語系資源。Power BI 會依使用者語系顯示欄位槽名稱、格式面板項目與 landing page 文字。

### 右鍵選單

在甘特長條上按右鍵可開啟 Power BI context menu，使用 Power BI 提供的標準操作。

### 跨 visual 選取

點擊甘特長條可選取對應資料點，並將選取狀態傳給 Power BI host，讓其他 visual 可以依 Power BI 的互動設定回應。

### 鍵盤操作

可使用 Tab 聚焦篩選按鈕與甘特長條。按 Enter 或 Space 可觸發選取，按 Shift+F10 或 Context Menu 鍵可在甘特長條上開啟 Power BI context menu。

## English

### Required Field

Add a field to:

- Task: the task, activity, project item, or row label to display in the calendar Gantt visual.

### Optional Category Fields

You can add fields to:

- Color Category: groups tasks by category and drives the legend.
- Bar Label Before Time: text shown before a bar.
- Bar Label After Time: text shown after a bar.
- Tooltips: additional fields shown in the hover tooltip. Multiple fields can be added.

### Time Range Fields

The visual supports up to three time ranges:

- Time Start 1
- Time End 1
- Time Start 2
- Time End 2
- Time Start 3
- Time End 3

Each range should use date/time-compatible values. A start value and end value should represent the same schedule segment.

### Formatting Options

#### Labels

- Time 1 Label
- Time 2 Label
- Time 3 Label
- Legend Title

#### Bar Label Style

- Font Size
- Font Weight
- Font Family
- Font Color

#### Layout

- Week Height
- Bar Stack Mode
- Time 1 Height
- Time 2 Height
- Time 3 Height
- Time 1 Opacity
- Time 2 Opacity
- Time 3 Opacity
- Time 1 Radius
- Time 2 Radius
- Time 3 Radius

### Additional Tooltips

The default hover information uses the official Power BI tooltip service and includes the task, category, time segment, start time, and end time. The Tooltips field well is for additional fields users want to inspect, such as owner, status, department, notes, or progress.

### Bar Stack Mode

Use the Bar Stack Mode setting to control how bars are placed:

- 0: Separate
- 1: Overlay by task
- 2: Overlay all

### Troubleshooting

If no bars are shown, check that:

- Task is populated.
- At least one start/end time range is populated.
- Start and end values are valid date/time values.
- The visual is large enough to display the calendar layout.

If labels are difficult to read, adjust:

- Font Size
- Font Color
- Time range opacity
- Bar heights

### High Contrast Mode

When Power BI high contrast mode is enabled, the visual uses the foreground, background, and border colors provided by Power BI instead of the regular color palette.

### Category Colors

In regular mode, Color Category values use colors from the Power BI color palette. This helps the visual align with report themes and Power BI's default color behavior.

### Landing Page

When required fields are missing or no valid schedule data is available, the visual displays bilingual guidance to help users add the required fields or fix date values.

### Localization

The visual includes en-US and zh-TW localization resources. Power BI uses the user's locale to display field well names, formatting pane items, and landing page text.

### Context Menu

Right-click a schedule bar to open the Power BI context menu with standard Power BI actions.

### Cross-Visual Selection

Click a schedule bar to select its data point and pass the selection state to the Power BI host, allowing other visuals to respond according to Power BI interaction settings.

### Keyboard Navigation

Use Tab to focus filter buttons and schedule bars. Press Enter or Space to select, and press Shift+F10 or the Context Menu key on a schedule bar to open the Power BI context menu.
